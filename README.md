Catálogo de Livros - Interação via Console

Visão Geral

Este projeto permite interação textual via console para busca e gerenciamento de livros através de uma API específica.

Funcionalidades

Buscar livros: Consultar livros por título, autor ou gênero na API.

Listar livros salvos: Exibir livros armazenados no banco de dados.

Adicionar livro aos favoritos: Salvar livros de interesse.

Remover livro dos favoritos: Excluir livros da lista de favoritos.

Sair: Finalizar o programa.

Passos para Completar o Desafio

1. Configuração do Ambiente Java

Instalar o Java JDK

Configurar variáveis de ambiente

Instalar um IDE como IntelliJ IDEA ou Eclipse

2. Criação do Projeto

Criar um projeto Java

Configurar dependências (Gson para JSON, JDBC para banco de dados)

3. Consumo da API

Identificar uma API de livros (Google Books API)

Implementar requisições HTTP

4. Análise da Resposta JSON

Utilizar Gson ou Jackson para desserialização

Extrair título, autor e descrição

5. Banco de Dados

Configurar MySQL, PostgreSQL ou SQLite

Criar tabelas para armazenar livros favoritos

Implementar consultas para salvar e recuperar dados

6. Exibição de Resultados

Criar interface interativa via console

Permitir que o usuário visualize e interaja com os livros

Tecnologias Utilizadas

Java 11+

Gson/Jackson para JSON

HttpURLConnection, OkHttp ou Apache HttpClient

Banco de dados relacional

JDBC para conexão

Como Executar

Clone o repositório: git clone <URL_DO_REPOSITORIO>

Configure o banco de dados

Compile: javac Main.java

Execute: java Main
