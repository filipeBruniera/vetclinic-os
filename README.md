# VetClinic - Sistema de Gestão para Clínicas Veterinárias

## Descrição

O **VetClinic** é uma aplicação web desenvolvida em Laravel, destinada ao gerenciamento de clínicas veterinárias. A aplicação permite realizar o controle de agendamentos de consultas, cadastro de pacientes (animais), gerenciamento de funcionários e controle financeiro.

Este sistema foi desenvolvido utilizando **Docker** para criar um ambiente de desenvolvimento consistente e fácil de configurar. O Docker Compose é utilizado para configurar os containers do Laravel, MySQL, Redis e Mailpit.

## Tecnologias Utilizadas

- **Laravel**: Framework PHP para desenvolvimento de aplicações web.
- **Docker**: Para containerizar a aplicação e facilitar o setup do ambiente.
- **MySQL**: Banco de dados relacional utilizado para armazenar os dados da aplicação.
- **Redis**: Sistema de cache para melhorar a performance.
- **Mailpit**: Sistema de captura de e-mails para testes.
- **Adminer**: Interface web para gerenciar o banco de dados MySQL.

## Funcionalidades

- **Gerenciamento de Pacientes**: Cadastro e controle de informações sobre os animais.
- **Agendamentos de Consultas**: Marcação de consultas veterinárias.
- **Gerenciamento de Funcionários**: Cadastro de veterinários e atendentes.
- **Controle Financeiro**: Controle de pagamentos e recebimentos.
- **Integração com E-mail**: Envio de e-mails utilizando o Mailpit para testes.

## Pré-Requisitos

Antes de rodar a aplicação, é necessário ter o Docker e o Docker Compose instalados na sua máquina. Para isso, siga as instruções abaixo:

- [Instalar Docker](https://docs.docker.com/get-docker/)
- [Instalar Docker Compose](https://docs.docker.com/compose/install/)
