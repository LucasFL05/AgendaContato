# Agenda de Contatos

## Introdução
Este projeto é uma aplicação web desenvolvida em Java para gerenciar uma lista de contatos. Os usuários podem adicionar, editar, excluir e visualizar contatos, além de gerar relatórios em formato PDF.

## Tecnologias Utilizadas
- Linguagem de Programação: Java
- Frameworks/Libraries: Servlets, JSP, JDBC, iTextPDF
- Banco de Dados: MySQL
- Ambiente de Desenvolvimento: Eclipse IDE
- Servidor Web: Apache Tomcat
- Gerenciamento de Dependências: Maven

## Estrutura do Projeto
O projeto segue o padrão MVC (Model-View-Controller), com os seguintes pacotes principais:
- `controller`: Servlets para gerenciar requisições HTTP.
- `model`: Classes JavaBeans e DAO para representar o modelo de dados e acessar o banco de dados.
- `webapp`: Arquivos JSP e recursos estáticos para a interface de usuário.

## Funcionalidades Principais
- Adicionar, editar, excluir e visualizar contatos.
- Gerar relatórios em PDF com a lista de contatos.

## Como Executar o Projeto
1. Importe o projeto para o Eclipse IDE.
2. Configure o servidor Apache Tomcat no Eclipse.
3. Configure o banco de dados MySQL e ajuste as configurações de conexão no arquivo `DAO.java`.
4. Execute o script SQL fornecido para criar o banco de dados e inserir dados iniciais.
5. Inicie o servidor Tomcat e execute a aplicação.
