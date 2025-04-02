# Modelo ER Estendido para E-commerce

Este repositório contém o modelo de Entidade-Relacionamento (ER) estendido desenvolvido para um sistema de banco de dados de e-commerce. Este projeto foi criado como parte de um desafio do curso de Banco de Dados da DIO.me.

## Visão Geral

O modelo ER estendido descreve as principais entidades e relacionamentos necessários para gerenciar as operações de uma plataforma de e-commerce. Ele foi projetado para ser funcional e simples, visando proporcionar uma base sólida para a construção de um banco de dados eficiente.

## Entidades Principais e Atributos

- **Cliente**: Representa os clientes que utilizam a plataforma.
  - Atributos: ID, Nome, Email, Endereço, Telefone

- **Produto**: Representa os produtos disponíveis para venda.
  - Atributos: ID, Nome, Descrição, Preço, Estoque

- **Pedido**: Representa os pedidos realizados pelos clientes.
  - Atributos: ID, ID_Cliente, Data, Status

- **Pagamento**: Representa os pagamentos realizados pelos clientes.
  - Atributos: ID, ID_Pedido, Tipo, Status, Valor

- **Entrega**: Representa as entregas dos pedidos.
  - Atributos: ID, ID_Pedido, Data_Envio, Data_Entrega, Status

## Principais Relacionamentos

- **Cliente-Pedido**: Um cliente pode realizar múltiplos pedidos.
- **Pedido-Produto**: Cada pedido pode conter múltiplos produtos.
- **Pedido-Pagamento**: Cada pedido tem um pagamento associado.
- **Pedido-Entrega**: Cada pedido tem uma entrega associada.

## Objetivo do Projeto

Este modelo pode ser utilizado como referência para o planejamento e implementação de um banco de dados completo para e-commerce. Ele cobre desde o gerenciamento de clientes até a entrega e pagamento, promovendo um sistema organizado e eficiente.

## Como Usar

1. Clone o repositório para a sua máquina local.
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
