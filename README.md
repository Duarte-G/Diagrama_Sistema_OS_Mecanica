# Diagrama ER - Sistema de Ordens de Serviço para Oficina Mecânica

Este repositório contém o diagrama para um sistema de gerenciamento de ordens de serviço em uma oficina mecânica. O projeto foi desenvolvido como exercício de modelagem de banco de dados utilizando o MySQL Workbench.

## Descrição do Sistema

O sistema tem como objetivo controlar e organizar os atendimentos realizados por uma oficina mecânica. Nele, é possível:

- Cadastrar clientes e seus veículos
- Emitir ordens de serviço (OS) para consertos ou revisões
- Associar serviços e peças utilizados em cada OS
- Registrar equipes de mecânicos e suas especialidades
- Calcular o valor total de cada ordem a partir dos serviços e peças aplicados

## Entidades Principais

- **Cliente**: Pessoa que leva um ou mais veículos à oficina
- **Veículo**: Carro ou moto pertencente ao cliente
- **OS (Ordem de Serviço)**: Documento que registra o atendimento, serviços e peças
- **Equipe**: Grupo de mecânicos responsáveis por executar a OS
- **Mecânico**: Profissional com especialidade associada a uma ou mais equipes
- **Serviço**: Tarefa de mão de obra, com valor pré-definido
- **Peça**: Item que pode ser utilizado na execução da OS

<p align="center">
  <img src="https://github.com/user-attachments/assets/a731f738-ab6a-4d2f-8f96-bdaa70b700bd">
</p>
