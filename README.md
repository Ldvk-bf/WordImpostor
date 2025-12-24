# Quem é o Impostor? 🕵️‍♂️

Bem-vindo ao **Quem é o Impostor?**, um jogo social de dedução, blefe e rapidez mental, ideal para grupos de amigos e festas.

> [!IMPORTANT]
> **Aviso:** Este projeto é apenas uma brincadeira e um experimento tecnológico. Foi desenvolvido com o auxílio da inteligência artificial **Gemini**. O objetivo é puramente recreativo.

## 🎮 Como Funciona o Jogo

O jogo coloca um grupo de pessoas num cenário de desconfiança, onde a maioria partilha um segredo e uma minoria tenta infiltrar-se sem ser detetada.

### 1. Preparação
* O grupo define o número total de jogadores.
* Define-se a quantidade de **Impostores** infiltrados (ex: 3 impostores para 12 jogadores).

### 2. A Palavra Secreta
* **Inocentes:** Todos os jogadores inocentes recebem a **mesma palavra secreta** (ex: "Melancia").
* **Impostores:** Não recebem a palavra. O sistema apenas os informa de que são os impostores.

### 3. A Dinâmica da Rodada
Cada jogador, um de cada vez, deve dizer **apenas uma palavra** relacionada com a palavra secreta.
* **Inocentes:** Devem escolher uma palavra que prove aos outros inocentes que eles sabem o segredo, mas que não seja óbvia demais para o impostor.
* **Impostores:** Como não sabem a palavra, devem prestar atenção às pistas dos outros e tentar dizer algo que "encaixe" no tema para não serem descobertos.

## 🗳️ Sistema de Votação e Vitória

A votação é realizada de forma individual e sucessiva. O dispositivo deve passar por cada jogador para que este registe os seus votos secretamente.

### Processo de Votação
1. Cada jogador vota em quem suspeita serem os impostores.
2. O número de votos disponíveis para cada um é igual ao número de impostores da partida.
3. O sistema soma todos os votos e gera um ranking dos jogadores mais votados (**Top Votos**).

### Critérios de Resultado
A vitória é decidida com base no equilíbrio entre acertos e erros no grupo dos mais votados:

| Resultado | Condição |
| :--- | :--- |
| **Vitória dos Inocentes** | $\text{Impostores desmascarados} \ge \text{Inocentes acusados}$ |
| **Vitória dos Impostores** | $\text{Impostores desmascarados} < \text{Inocentes acusados}$ |

> **Nota:** Se os inocentes acusarem mais pessoas erradas do que acertarem nos impostores no grupo final, os impostores ganham a partida.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser leve e funcional em qualquer navegador, utilizando:

* **HTML5 e CSS3** (com Tailwind CSS)
* **JavaScript Nativo** (Vanilla JS)
* **Lucide Icons** (Interface visual)
* **Gemini AI** (Lógica de jogo e geração de palavras)

---
**Divirta-se a encontrar os traidores!**
