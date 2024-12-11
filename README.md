Desafio de Projeto: Modelagem Conceitual para Sistema de E-commerce

Este repositório contém o esquema de banco de dados e a descrição do projeto conceitual para o sistema de E-commerce de um desafio proposto pela DIO.me. O objetivo é fornecer uma solução eficiente para o gerenciamento de clientes, pedidos, produtos, pagamentos, estoque e entregas, considerando as necessidades do desafio proposto.

Contexto do Projeto

Narrativa do Produto
- Os produtos são vendidos por uma única plataforma online, mas podem ter fornecedores diferentes (terceiros).
- Cada produto possui um fornecedor.
- Um ou mais produtos podem compor um pedido.

Narrativa do Cliente
- O cliente pode se cadastrar no site utilizando CPF (Pessoa Física) ou CNPJ (Pessoa Jurídica).
- O endereço do cliente determina o valor do frete.
- Um cliente pode realizar mais de um pedido, cada um com um período de carência para devolução dos produtos.

Narrativa do Pedido
- Os pedidos são criados por clientes e contêm informações como endereço de entrega, status e frete.
- Um ou mais produtos compõem o pedido.
- O pedido pode ser cancelado.

Narrativa do Fornecedor & Estoque
- Cada fornecedor pode disponibilizar diferentes produtos para venda.
- O estoque deve registrar os produtos e suas respectivas quantidades por local.

Narrativa de Pagamento e Entrega
- A forma de pagamento pode ser "Cartão", "Pix", "Boleto" ou "Transferência".
- Os pagamentos realizados por cartão incluem informações específicas como número do cartão, validade e nome do titular.
- A entrega possui status, código de rastreio e datas previstas.

Possíveis consultas:
Com base no modelo proposto, o banco permite:
1. Identificar os produtos mais vendidos e seus respectivos fornecedores.
2. Rastrear pagamentos por tipo de pagamento (ex.: Pix, Cartão).
3. Monitorar entregas em andamento, com status e código de rastreio.
4. Consultar o estoque por local e produto.
5. Listar clientes por tipo (PF ou PJ) e seus pedidos.

Conclusão
Este modelo foi projetado para atender às necessidades do sistema de e-commerce, garantindo organização dos dados e eficiência nas operações. Ele oferece flexibilidade para expansões futuras e facilita análises comerciais e operacionais.
