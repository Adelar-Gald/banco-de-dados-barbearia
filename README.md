# Projeto de Banco de Dados - Barbearia

## Descrição do Projeto

Este projeto apresenta a modelagem conceitual de um banco de dados para uma barbearia. O objetivo é organizar as principais informações do sistema, permitindo o cadastro de clientes, o registro de agendamentos, a definição dos serviços oferecidos e a relação entre profissionais e serviços executados.

O modelo foi desenvolvido com base nas regras de negócio de uma barbearia, considerando que o cliente realiza um agendamento, o agendamento registra o serviço desejado e os profissionais podem executar diferentes tipos de serviços.

---

## Objetivo do Banco de Dados

O objetivo deste banco de dados é estruturar e organizar as informações essenciais para o funcionamento de uma barbearia, facilitando:

- o cadastro de clientes;
- o controle de agendamentos;
- o registro dos serviços oferecidos;
- a identificação dos profissionais disponíveis;
- a relação entre os profissionais e os serviços que podem ser executados.

---

## Regras de Negócio

As principais regras de negócio consideradas neste projeto são:

1. Um cliente pode realizar vários agendamentos.
2. Cada agendamento pertence a um único cliente.
3. Cada agendamento registra apenas um serviço.
4. Um mesmo tipo de serviço pode aparecer em vários agendamentos.
5. Um profissional pode executar vários serviços.
6. Um mesmo serviço pode ser executado por vários profissionais.

---

## Entidades do Modelo Conceitual

As entidades principais do projeto são:

- **CLIENTE**
- **AGENDAMENTO**
- **SERVICO**
- **PROFISSIONAL**

---

## Relacionamentos

- **CLIENTE faz AGENDAMENTO**
- **AGENDAMENTO registra SERVICO**
- **PROFISSIONAL executa SERVICO**

---

## Arquivos do Projeto

Este repositório contém os seguintes arquivos:

- `README.md` → documentação do projeto;
- `diagrama_barbearia.puml` → código PlantUML do modelo conceitual;
- `diagrama_barbearia.png` → imagem gerada do diagrama.

---

## Ferramentas Utilizadas

- **Visual Studio Code (VS Code)** para edição do código do diagrama;
- **Extensão PlantUML** para criação e visualização do modelo conceitual;
- **GitHub** para armazenamento e versionamento do projeto.
---

## Autor

Projeto desenvolvido para atividade acadêmica da disciplina de Banco de Dados.
