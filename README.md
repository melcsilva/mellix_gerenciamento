# Money Management App

Aplicação full stack para gerenciamento financeiro pessoal, desenvolvida com **Java, Spring Boot, React e MySQL**.  
O sistema permite controlar receitas e despesas, analisar dados financeiros e gerenciar transações de forma simples e organizada.

## Funcionalidades

- Cadastro e login de usuários
- Autenticação com JWT
- Gerenciamento de receitas e despesas
- Validação de dados no backend
- Upload de foto de perfil com Cloudinary
- Seleção personalizada de emojis para categorias
- Análise de dados com gráficos em React
- Download de transações
- Envio de transações por e-mail
- Lembretes diários por e-mail

## Tecnologias Utilizadas

### Frontend
- React.js
- Axios
- Tailwind CSS
- Lucide React
- React Hot Toast
- Emoji Picker
- React Charts

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- JWT Authentication

### Banco de Dados
- MySQL

### Outros Serviços
- Cloudinary
- E-mail Service

## Objetivo do Projeto

Este projeto foi criado com o objetivo de praticar o desenvolvimento de uma aplicação full stack completa, integrando frontend, backend, banco de dados, autenticação, upload de arquivos e envio de e-mails.

Além disso, o projeto também tem como foco melhorar minhas habilidades com Java, Spring Boot, React e construção de APIs REST seguras.

## Principais Recursos

### Autenticação
O sistema possui cadastro e login de usuários, utilizando Spring Security com autenticação baseada em JWT.

### Controle Financeiro
O usuário pode adicionar, visualizar e gerenciar receitas e despesas, mantendo um controle mais claro sobre sua vida financeira.

### Dashboard com Gráficos
A aplicação apresenta análises visuais dos dados financeiros utilizando gráficos no React.

### Perfil do Usuário
O usuário pode personalizar seu perfil com upload de imagem, armazenada na Cloudinary.

## Como Executar o Projeto

### Backend

```bash
cd backend
mvn spring-boot:run
