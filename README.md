# 🎵 Sistema Musical

## 📋 Descrição do Projeto

O **Sistema Musical** é uma aplicação web desenvolvida em PHP, integrada a um banco de dados MySQL, que permite cadastrar, editar, excluir e visualizar artistas e músicas.

O sistema funciona como uma biblioteca musical, permitindo organizar informações sobre artistas, álbuns, gêneros musicais, letras e links de vídeos do YouTube.

## 🎯 Objetivo

Desenvolver um sistema para gerenciamento de uma biblioteca musical, colocando em prática conceitos de desenvolvimento web, integração com banco de dados, operações CRUD e autenticação de usuários.

## ⚙️ Funcionalidades

### 🔐 Login e autenticação
- Tela de login para acesso ao sistema.
- Verificação de usuário e senha.
- Controle de sessão.
- Opção para sair do sistema.

### 🎤 Gerenciamento de artistas
- Cadastrar novos artistas.
- Editar informações dos artistas.
- Excluir artistas.
- Adicionar fotos dos artistas.
- Informar nome, gênero musical e país.

### 🎵 Gerenciamento de músicas
- Cadastrar músicas vinculadas aos artistas.
- Editar informações das músicas.
- Excluir músicas.
- Adicionar capa do álbum.
- Informar título, álbum, gênero e letra.
- Adicionar links de vídeos do YouTube.

### 🎼 Biblioteca musical
- Visualizar as músicas cadastradas.
- Pesquisar por título, álbum ou artista.
- Filtrar músicas por artista.
- Filtrar músicas por gênero musical.
- Acessar vídeos do YouTube relacionados às músicas.

## 🛠️ Tecnologias utilizadas

- **HTML5:** estrutura das páginas.
- **CSS3:** estilização e organização visual.
- **PHP:** programação e funcionamento do sistema.
- **MySQL:** armazenamento e gerenciamento dos dados.
- **MySQLi:** conexão entre PHP e banco de dados.
- **XAMPP:** ambiente de desenvolvimento local.

## 🗄️ Banco de Dados

O projeto utiliza o banco de dados `sistema_musical_v2`, composto por três tabelas principais:

| Tabela | Função |
|---|---|
| usuarios | Armazena os dados de acesso ao sistema. |
| artistas | Armazena as informações dos artistas. |
| musicas | Armazena as informações das músicas. |

As músicas possuem relacionamento com os artistas por meio de uma chave estrangeira (`artista_id`).

## 🚀 Como executar o projeto

1. Instale o XAMPP no computador.
2. Inicie os serviços Apache e MySQL.
3. Copie a pasta `sistema_musical` para a pasta `htdocs` do XAMPP.
4. Acesse o phpMyAdmin pelo endereço `http://localhost/phpmyadmin`.
5. Importe o arquivo `bd.sql` para criar o banco de dados e suas tabelas.
6. Verifique as configurações de conexão no arquivo `conexao.php`.
7. Abra o navegador e acesse:

`http://localhost/sistema_musical/`

## 📁 Estrutura do Projeto

- `index.php` – Menu principal.
- `login.php` – Tela de login.
- `logout.php` – Encerramento da sessão.
- `cadastro_artista.php` – Cadastro e gerenciamento de artistas.
- `cadastro_musica.php` – Cadastro e gerenciamento de músicas.
- `listagem_musicas.php` – Biblioteca musical e filtros.
- `conexao.php` – Conexão com o banco de dados.
- `valida_sessao.php` – Validação do acesso ao sistema.
- `geraSenha.php` – Geração de senha.
- `teste_conexao.php` – Teste de conexão com o banco.
- `bd.sql` – Script de criação do banco de dados.
- `styles.css` – Estilos das páginas.
- `img/` – Imagens dos artistas e capas das músicas.

## 📚 Conhecimentos desenvolvidos

Durante o desenvolvimento da atividade, foram trabalhados conceitos como:

- Programação em PHP.
- Integração entre PHP e MySQL.
- Operações CRUD (Create, Read, Update e Delete).
- Criação e utilização de tabelas relacionadas.
- Chaves primárias e estrangeiras.
- Autenticação e controle de sessões.
- Upload e redimensionamento de imagens.
- Consultas SQL e filtros de pesquisa.
- Validação de formulários.

## ✅ Conclusão

O desenvolvimento do Sistema Musical permitiu colocar em prática os conhecimentos adquiridos em desenvolvimento web e banco de dados. A atividade ajudou a compreender melhor como funciona a integração entre PHP e MySQL, além de trabalhar com cadastros, consultas, alterações e exclusões de informações.

O resultado é um sistema que facilita a organização e o gerenciamento de artistas e músicas de maneira simples e organizada.

---
