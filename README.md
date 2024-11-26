Desafio Refinando um Projeto Conceitual de Banco de Dados – Oficina Mecânica | Instrutora: Juliana Mascarenhas

Objetivo do diagrama: representa o modelo de banco de dados para a gestão de uma oficina mecânica, com o objetivo de organizar e estruturar informações relacionadas a clientes, veículos, serviços, mecânicos e ordens de serviço.

![oficina mecanica](https://github.com/user-attachments/assets/d9294759-8653-4171-ab12-3ccbe71f7e8d)

Narrativas: 

Cliente: Um cliente pode ter um ou mais veículos, estabelecendo um relacionamento 1:N.

Veículos: Cada veículo está associado a um cliente.
Relacionamento com Tipos de Serviços através da tabela associativa Veiculos_has_Tipos de Serviços: Define quais tipos de serviços são aplicáveis a cada veículo.

Tipos de Serviços: indicando que um serviço pode ser aplicado a vários veículos e um veículo pode ter diversos serviços.

Ordem de Serviço (OS): Estabelece o vínculo entre uma ordem de serviço e os serviços executados.
Inclui detalhes financeiros e de status das ordens.

Execução de Serviços: Centraliza os dados sobre quais serviços foram executados, por quais mecânicos, para quais ordens.

Mecânicos (Funcionários): Associa mecânicos aos serviços realizados e histórico.
