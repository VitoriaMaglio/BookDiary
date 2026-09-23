# BookDiary
Sua biblioteca pessoal para registrar leituras, organizar livros e guardar suas anotações.


## Descrição do Aplicativo

O BookDiary é uma biblioteca pessoal digital voltada para leitores, permitindo registrar livros lidos, acompanhar o progresso da leitura e salvar comentários e anotações durante a experiência de leitura.

Propósito: oferecer um espaço organizado para gerenciar leituras, registrar impressões e manter um histórico literário.

Público-alvo: leitores de todas as idades.
Feature do Firebase: Firebase Analytics, utilizado para coletar dados de uso do aplicativo, como funcionalidades mais acessadas, quantidade de livros cadastrados e frequência de utilização, auxiliando na melhoria da experiência do usuário.

## Protótipo Inicial

O protótipo inicial do BookDiary será composto por três telas que representam o fluxo principal da aplicação, oferecendo uma experiência simples e intuitiva para o usuário:

• Tela de Login: autenticação por e-mail e senha, utilizando JWT (JSON Web Token) para garantir acesso seguro e gerenciamento da sessão do usuário.

• Tela Inicial (Minha Biblioteca): exibe a coleção de livros cadastrados, com pesquisa, filtros por status (Lendo, Lidos e
Favoritos) e opção para adicionar novos livros.

• Tela de Detalhes do Livro: apresenta as informações do livro e permite registrar comentários, anotações, atualizar o progresso da leitura e alterar seu status.
Escalabilidade

 Telas e Funcionalidades
1. Tela de Login
Objetivo: autenticar o usuário e permitir acesso à aplicação.

Elementos
- Logo do BookDiary

- Campo de e-mail

- Campo de senha

- Botão Entrar

- Link Criar conta

Features
- Login com e-mail e senha

- Autenticação utilizando JWT (JSON Web Token)

- Controle de sessão e acesso seguro

2. Tela Inicial — Minha Biblioteca
Objetivo: exibir e organizar os livros cadastrados pelo usuário.

Elementos
- Barra de pesquisa

- Lista de livros

- Botão Adicionar Livro

- Filtros por status (Lendo, Lidos e Favoritos)

Features
- Cadastro e organização de livros

- Pesquisa por título

- Filtragem por status da leitura
  
- Monitoramento de uso com Firebase Analytics

3. Tela de Detalhes do Livro
Objetivo: acompanhar o progresso da leitura e registrar informações sobre cada livro.

Elementos
- Capa do livro

- Título e autor

- Status da leitura

- Campo para comentários e anotações

- Botão Salvar

Features
- Registro de comentários e anotações

- Atualização do progresso da leitura

- Alteração do status do livro

- Edição das informações cadastradas

## Segurança

A autenticação será baseada em JWT, garantindo proteção das rotas e controle de acesso. As senhas serão armazenadas de forma criptografada e os tokens possuirão tempo de expiração, reforçando a segurança dos dados dos usuários.

## Integrantes do grupo:

Vitória Valentina Maglio

Marina Magalhães 

Nathan Gonçalves Pereira 

João Pedro Bitencourt
