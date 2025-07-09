# Adivinhe React

Jogo de adivinhação de palavras desenvolvido em React, onde o usuário deve descobrir a palavra correta a partir de uma dica, com número limitado de tentativas.

## Sobre o Projeto

Esta aplicação é um jogo simples de adivinhação de palavras. A cada rodada, o usuário recebe uma dica relacionada a uma palavra oculta e deve tentar adivinhar, letra por letra, qual é a palavra.

- A cada tentativa, o usuário informa uma letra.
- Se a letra estiver na palavra, ela é revelada na posição correta.
- Se não estiver, a tentativa é contabilizada.
- O usuário pode ver as letras já utilizadas e se cada uma estava correta ou não.
- O jogo termina quando a palavra é descoberta ou quando as tentativas acabam.
- É possível reiniciar o jogo a qualquer momento.

## Stack Utilizada

- **React**: Biblioteca para construção da interface de usuário.
- **TypeScript**: Superset do JavaScript com tipagem estática.
- **Vite**: Ferramenta de build e desenvolvimento rápido para projetos front-end.
- **CSS Modules**: Estilização modular e escopada aos componentes.

## Como Executar

Siga os passos abaixo para executar o projeto localmente em sua máquina:

1. **Clone o repositório**  
   Se ainda não fez isso, clone o repositório para o seu computador:
   ```bash
   git clone https://github.com/pedro18x/Adivinhe-React.git
   cd Adivinhe-React
1. Instale as dependências:
   ```bash
   npm install
   ```
2. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
3. Acesse a aplicação em `http://localhost:5173` (ou porta indicada no terminal).

## Créditos

Desenvolvido por **Pedro Ernesto** durante o curso Fullstack da Rocketseat.
