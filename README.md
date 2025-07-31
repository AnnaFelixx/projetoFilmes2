# Projeto: Aluguel de filmes em swift (CLI)

Este projeto é um sistema simples de cadastro de filmes desenvolvido em **Swift** para ser executado via terminal (CLI – Command Line Interface).

O sistema permite:
- Cadastrar novos filmes com diversas informações
- Listar todos os filmes cadastrados
- Buscar filmes pelo nome
- Visualizar detalhes de um filme específico

---

## Funcionalidades

O sistema usa uma estrutura `struct Filme` para representar os filmes, contendo:

- `nome`: Nome do filme
- `ano`: Ano de lançamento
- `sinopse`: Pequena descrição
- `genero`: Gênero do filme
- `diretor`: Nome do diretor
- `valor`: Valor de aluguel

Valida se cada campo foi preenchido corretamente antes de salvar.

---

### 1. Cadastrar Filme
O usuário insere os dados pelo terminal. O sistema valida cada entrada e só cadastra se todos os campos forem válidos.

### 2. Listar Filmes
Exibe todos os filmes cadastrados, com a opção de:
- Procurar um filme específico
- Voltar ao menu principal

### 3. Buscar Filme
O usuário digita parte do nome e o sistema retorna todos os filmes que correspondem à busca (ignora maiúsculas/minúsculas).

### 4. Ver Detalhes
Após a busca, o usuário pode escolher um filme para ver seus detalhes completos (sinopse, gênero, diretor, etc.).

### 5. Menu Principal
O sistema apresenta um menu interativo com as opções:
