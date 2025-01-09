# Projeto_modelagem_Biblioteca

#  💻 Sistema de Gestão de Biblioteca - Modelagem de Banco de Dados

Este repositório contém a modelagem de banco de dados para um Sistema de Gestão de Biblioteca. O objetivo do projeto é fornecer uma solução eficiente para gerenciar o acervo de livros, usuários, funcionários e operações de empréstimos em uma biblioteca.

# Objetivo do Projeto

O sistema de gestão foi projetado para atender as seguintes necessidades de uma biblioteca:

Cadastro e gerenciamento de livros disponíveis no acervo.
Registro de usuários que utilizam os serviços da biblioteca.
Controle de funcionários responsáveis por registrar empréstimos e devoluções.
Monitoramento de empréstimos, incluindo status e prazos de devolução.
Registro de histórico de empréstimos realizados.

# Estrutura do Banco de Dados

# Entidades

O banco de dados é composto pelas seguintes tabelas principais:

Livro

Armazena informações sobre os livros disponíveis no acervo, incluindo título, autor, gênero, ano de publicação, editora e quantidade em estoque.

Usuário

Contém os dados dos usuários cadastrados, como nome, CPF, endereço e contato.

Funcionário

Registra os funcionários da biblioteca, responsáveis por registrar empréstimos e outras operações.

Empréstimo

Controla as transações de empréstimo, incluindo data de empréstimo, data prevista de devolução e status.

LivroEmpréstimo

Relaciona os livros aos empréstimos realizados, permitindo que um empréstimo contenha vários livros.


# Relacionamentos

Um usuário pode realizar vários empréstimos.
Um funcionário pode registrar vários empréstimos.
Um empréstimo pode conter vários livros.
Um livro pode estar associado a vários empréstimos diferentes.

# Recursos 

Este modelo pode ser utilizado para:

Implementação de sistemas de gerenciamento de bibliotecas físicas ou digitais.
Monitoramento de prazos de devolução e controle de atrasos.
Registro histórico de movimentação do acervo.


# Tecnologias Recomendadas

Este projeto foi modelado para ser utilizado com sistemas de gerenciamento de banco de dados relacionais (RDBMS) como:

MySQL
PostgreSQL
SQL Server
SQLite


# Como Usar

Clone este repositório:

git clone https://github.com/seu-usuario/gestao-biblioteca.git

Importe o arquivo SQL (se disponível) no seu banco de dados.
Customize o modelo conforme a necessidade da sua biblioteca.

# Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

