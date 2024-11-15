# Modelo de Banco de Dados para E-commerce
Este projeto apresenta a modelagem de um banco de dados para gerenciar operações de um sistema de e-commerce. O modelo foi desenvolvido para armazenar informações sobre clientes, fornecedores, produtos, pedidos, pagamentos e entregas.

## Principais Tabelas e Relacionamentos
- Cliente: Armazena dados de clientes (PF ou PJ) e está relacionada a pedidos e formas de pagamento.
- Pedido: Registra compras realizadas, associadas a clientes, produtos e entregas.
- Produto: Representa itens vendidos, relacionados a fornecedores, estoques e pedidos.
- Entrega: Gerencia status e código de rastreio de cada pedido.
- Forma de Pagamento: Permite que clientes registrem múltiplas formas de pagamento.
- Estoque: Controla a quantidade de produtos armazenados em diferentes locais.
## Destaques
- Normalização e clareza nas relações entre entidades.
- Suporte a múltiplos fornecedores e vendedores terceirizados para produtos.
- Gestão de entregas com rastreamento e status atualizado.

Este modelo pode ser usado como base para sistemas de e-commerce de pequeno a médio porte. Contribuições são bem-vindas!