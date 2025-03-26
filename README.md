# Axis Challenge Backend Developer

<p align="center">
   <a href="#-introducao">Introdução</a> •
   <a href="#-cenario">Cenário</a> •
   <a href="#-regras-do-negocio">Regras do Negócio</a> •
   <a href="#-funcionalidades">Funcionalidades</a> •
   <a href="#-instrucoes-e-sugestoes">Instruções & Sugestões</a> •
   <a href="#-diferenciais">Diferenciais</a> •
   <a href="#-documentacao-organizacao-e-entrega">Documentação, Organização & Entrega</a> •
   <a href="#-duvidas">Dúvidas</a>
</p>

## 📚 Introdução

Este é um desafio `Hands-On` que tem como objetivo testar suas habilidades como `Backend Developer` com conhecimentos básicos em `DevOps`. O desafio faz parte do processo seletivo da [Axis Mobfintech](https://axis-mobfintech.com/).

## 🚀 Cenário

Você deverá desenvolver uma `REST API` que permita que cooperados de uma Cooperativa de Crédito mantenham uma lista de **Contatos Favoritos** associados à conta corrente da cooperativa.

## 🎯 Regras do Negócio

Cada contato favorito deve conter:

- Identificação do registro;
- Nome do contato;
- Tipo de chave Pix:
  - Apenas: CPF, CNPJ, E-mail, Telefone ou Chave Aleatória;
- Chave Pix.

A cooperativa deve permitir o cadastro de:

- Cooperativas (com nome e código);
- Cooperados (com nome e conta corrente);
- Contatos Favoritos (vinculados a um cooperado e sua conta corrente).

## ⚙️ Funcionalidades

A API deve fornecer serviços REST para:

- CRUD (Create, Read, Update, Delete) de **Cooperativas** (exclusão lógica);
- CRUD de **Cooperados** (exclusão lógica);
  - A pesquisa pode ser feita pelo **número da conta corrente** ou **nome do cooperado**;
- CRUD de **Contatos Favoritos** (exclusão física).

## 📌 Instruções e Sugestões

Espera-se que:

- O backend seja desenvolvido em **C# e .NET 8** (ou superior);
- Seja utilizado um **banco de dados relacional** como **PostgreSQL** ou **SQL Server**;
- A persistência seja implementada utilizando **Entity Framework Core** e **migrations**;
- A API seja documentada utilizando **Swagger/OpenAPI 3.0**;
- O sistema utilize **validação de dados** no backend;
- Padronização das mensagens de erro e sucesso da API;
- Os endpoints sigam as boas práticas de **RESTful APIs**.

## 💡 Diferenciais (itens opcionais)

- Utilização de padrões arquiteturais como **DDD, Clean Architecture ou Hexagonal**;
- Implementação de **Testes Unitários** e/ou **Testes de Integração**;
- Uso de **JWT** ou outro método seguro de autenticação;
- Configuração de **Docker** e/ou **Docker Compose** para facilitar a execução local;
- Configuração de um pipeline de **CI/CD** básico utilizando GitHub Actions ou outra ferramenta;
- Deploy automatizado para um ambiente cloud (exemplo: AWS, Azure ou GCP);
- Configuração de **monitoramento** ou **logs estruturados**.

## ✔️ Documentação, Organização e Entrega

- O projeto deve ser entregue via **repositório Git** (GitHub, GitLab ou Bitbucket);
- Criar um arquivo `README.md` contendo:
  - Tecnologias utilizadas;
  - Instruções para rodar o projeto localmente;
  - Instruções para rodar o projeto com Docker (se aplicável);
  - Como executar os testes (se houver);
- Adicionar um `.gitignore` adequado para o projeto;
- O **prazo limite para entrega é 27/03/2025 às 23h59**.

## ❓ Dúvidas?

Se tiver qualquer dúvida, entre em contato abrindo uma **Issue** no repositório do desafio.

Boa sorte! 🚀
