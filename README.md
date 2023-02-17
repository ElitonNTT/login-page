Página de Login com Barra de Progresso usando Vite, React e CSS.

Este é um projeto simples que consiste em uma página de login que apresenta campos para Nome, E-mail, Estado Civil e Gênero, além de uma barra de progresso que aumenta ou diminui de acordo com o preenchimento correto dos campos.

Como rodar o projeto?

Clone o repositório usando o comando git clone.

Na pasta raiz do projeto, execute o comando npm install para instalar as dependências.

Em seguida, execute o comando npm run dev para iniciar o servidor de desenvolvimento.

Abra o seu navegador e navegue até http://127.0.0.1:5173/ para visualizar a aplicação.

Funcionalidades:

A página de login permite que o usuário preencha os campos de Nome, E-mail, Estado Civil e Gênero. À medida que o usuário preenche cada campo corretamente, a barra de progresso aumenta proporcionalmente até atingir 100%. Se algum campo estiver preenchido incorretamente ou faltar preencher, a barra de progresso diminui proporcionalmente.

Estrutura do Projeto:

O projeto é composto pelos seguintes arquivos e diretórios:

src/App.jsx: Arquivo principal do projeto, que contém o componente React responsável por renderizar a página de login.

src/styles.css: Arquivo CSS global que define o estilo do projeto.

Algumas melhorias que podem ser implementadas no projeto:

Melhorias no design da página, como a adição de uma animação de transição para a barra de progresso.

Adição de uma mensagem de erro ou sucesso quando o usuário preenche todos os campos corretamente.