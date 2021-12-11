## **Sobre os datasets**
- ### **Conjunto de dados de clientes**

<p align='justify'>Este conjunto de dados contém informações sobre o cliente e sua localização. Use-o para identificar clientes únicos no conjunto de dados de pedidos e para encontrar o local de entrega dos pedidos.</p>

<p align='justify'>Em nosso sistema, cada pedido é atribuído a um ID de cliente único . Isso significa que o mesmo cliente obterá IDs diferentes para pedidos diferentes. O objetivo de ter um unique_id do cliente no conjunto de dados é permitir que você identifique os clientes que fizeram recompras na loja. Caso contrário, você descobrirá que cada pedido tem um cliente diferente associado.</p>

- ### **Conjunto de dados de geolocalização**

<p align='justify'>Este conjunto de dados contém informações dos CEPs brasileiros e suas coordenadas lat / lng. Use-o para traçar mapas e encontrar distâncias entre vendedores e clientes.</p>

- ### **Conjunto de dados de itens do pedido**

Este conjunto de dados inclui dados sobre os itens adquiridos em cada pedido.

Exemplo:
<p align='justify'>O order_id = 00143d0f86d6fbd9f9b38ab440ac16f5tem 3 itens (mesmo produto). Cada item tem o frete calculado de acordo com suas medidas e peso. Para obter o valor total do frete de cada pedido, basta somar.</p>

O valor total do item_de_pedido é: 21.33 * 3 = 63.99

O valor total do frete é: 15.10 * 3 = 45.30

O valor total do pedido (produto + frete) é: 45.30 + 63.99 = 109.29

- ### **Conjunto de dados de pagamentos**

Este conjunto de dados inclui dados sobre as opções de pagamento de pedidos.

- ### **Conjunto de dados de avaliações de pedidos**

Este conjunto de dados inclui dados sobre as avaliações feitas pelos clientes.

<p align='justify'>Depois que um cliente compra o produto na Olist Store, um vendedor é notificado para atender a esse pedido. Assim que o cliente recebe o produto, ou quando vence a previsão de entrega, o cliente recebe por e-mail uma pesquisa de satisfação onde pode dar um apontamento sobre a experiência de compra e anotar alguns comentários.</p>

- ### **Conjunto de dados do pedido**

<p align='justify'>Este é o conjunto de dados principal. Em cada pedido, você pode encontrar todas as outras informações.</p>

- ### **Conjunto de dados de produtos**

Este conjunto de dados inclui dados sobre os produtos vendidos pela Olist.

- ### **Conjunto de dados de vendedores**

<p align='justify'>Este conjunto de dados inclui dados sobre os vendedores que atenderam aos pedidos feitos na Olist. Use-o para encontrar a localização do vendedor e para identificar qual vendedor atendeu a cada produto.</p>

- ### **Tradução do nome da categoria**
Traduz o nome da categoria do produto para o inglês.