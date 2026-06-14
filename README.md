# 🎮 Jogo do Número Secreto

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

Um jogo interativo e responsivo de adivinhação desenvolvido em JavaScript puro, com estilização moderna em CSS e recursos de acessibilidade por voz.

---

## 📝 Sobre o Projeto

O **Jogo do Número Secreto** desafia o usuário a adivinhar um número gerado aleatoriamente pelo sistema. O projeto foi desenvolvido com foco em praticar a manipulação do DOM (Document Object Model), lógica de programação, estruturas condicionais, vetores (arrays) e funções recursivas.

### Principais Funcionalidades:
* **Gerador Aleatório Inteligente:** O jogo gera números aleatórios de 1 a 100 e armazena os números já sorteados em uma lista, garantindo que o mesmo número não seja escolhido novamente consecutivamente até que o limite seja atingido.
* **Dicas em Tempo Real:** O jogo informa ao jogador se o número secreto é maior ou menor que o chute atual.
* **Contador de Tentativas:** Mostra quantas tentativas foram necessárias para acertar, adaptando o texto para o singular ("tentativa") ou plural ("tentativas").
* **Acessibilidade (Text-to-Speech):** Utiliza a API do `ResponsiveVoice.js` para narrar os textos exibidos na tela em português do Brasil.
* **Responsividade:** Layout adaptável para telas menores (mobile/tablets), onde a imagem lateral é ocultada para priorizar a área de jogo.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da página.
* **CSS3:** Estilização com gradientes, efeitos de sombra, fontes customizadas via Google Fonts (`Chakra Petch` e `Inter`) e Media Queries para responsividade.
* **JavaScript (ES6):** Lógica do jogo, manipulação do DOM e controle de estado do jogo.
* **ResponsiveVoice API:** Biblioteca externa usada para a narração de voz.

---

## 🚀 Como Executar o Projeto

Você não precisa instalar nenhuma dependência externa, apenas um navegador web atualizado.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd NOME-DO-REPOSITORIO
    ```
3.  **Abra o arquivo principal:**
    Basta dar um duplo clique no arquivo `index.html` ou abri-lo diretamente com o seu navegador favorito.

---

## 🕹️ Como Jogar

1.  Ao iniciar, o jogo escolherá secretamente um número entre 1 e 100.
2.  Digite o seu palpite no campo numérico central.
3.  Clique no botão **"Chutar"**.
4.  O sistema lerá em voz alta e mostrará na tela se você acertou ou se o número secreto é maior/menor.
5.  Ao acertar, o botão **"Novo jogo"** será desbloqueado. Clique nele para reiniciar a partida com um novo número secreto.

---

## 📂 Estrutura de Arquivos

```text
├── index.html      # Estrutura HTML da aplicação
├── style.css       # Estilização visual e responsividade
├── app.js          # Lógica e comportamento em JavaScript
└── img/            # Imagens e texturas utilizadas no layout
    ├── ia.png
    ├── code.png
    └── Ruido.png
