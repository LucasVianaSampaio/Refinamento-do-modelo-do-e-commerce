# Sistema de Gestão de Pedidos

Este repositório contém o modelo de banco de dados de um sistema para gestão de pedidos. Ele inclui funcionalidades para o gerenciamento de clientes, fornecedores, produtos, estoques, formas de pagamento, e o acompanhamento de entregas. O modelo foi desenvolvido no MySQL Workbench e reflete as boas práticas de modelagem de dados.

## Regras de Negócio Implementadas

- Um cliente deve ser identificado como pessoa física (CPF) ou pessoa jurídica (CNPJ), mas não pode possuir ambas as informações.

- Clientes podem cadastrar múltiplas formas de pagamento.

- Cada entrega possui um status e um código de rastreio único.

## Modelagem do Banco de Dados

O projeto foi modelado utilizando MySQL Workbench e segue os padrões de normalização de dados. O modelo contempla as relações entre as entidades principais e suas restrições.
