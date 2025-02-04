# Desafio Técnico - TodoApp com React e TypeScript

Bem-vindo ao desafio técnico da VAAS! Neste projeto, você encontrará um **Todo App** construído com **React, TypeScript, Vite e Tailwind CSS**. O objetivo deste desafio é refatorar o código para melhorar a estrutura e a escalabilidade da aplicação.

## 🎯 Objetivos do Desafio

Você deverá realizar as seguintes melhorias no código:

1. **Substituir o state local por um React Context + useReducer**

   - Atualmente, o estado dos todos está sendo gerenciado via `useState` dentro do componente principal.
   - O desafio é criar um **contexto global** e utilizar `useReducer` para centralizar a lógica de estado.

2. **Componentizar o que for possível**

   - Identificar partes do código que podem ser transformadas em componentes reutilizáveis.
   - Melhorar a organização do projeto separando a lógica de UI e de negócios.

3. **Salvar os todos no LocalStorage usando um serviço assíncrono**
   - Garantir que os todos persistam entre recarregamentos da página utilizando o `localStorage`.
   - Implementar a lógica no novo contexto criado.

## 🛠 Tecnologias Utilizadas

- **React** + **TypeScript**
- **Vite** (para um ambiente de desenvolvimento rápido)
- **Tailwind CSS** (para estilização)

## 🚀 Como Rodar o Projeto

1. Clone este repositório:
   ```sh
   git clone https://github.com/gcostaefraim/desafio-vaas.git
   ```
2. Entre no diretório do projeto:
   ```sh
   cd desafio-vaas
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```sh
   npm run dev
   ```

## 📌 O que será avaliado?

- **Organização do código e boas práticas**
- **Uso adequado do Context API + useReducer**
- **Componentização e reusabilidade**
- **Persistência de dados no LocalStorage**

Divirta-se e bom desafio! 🚀
