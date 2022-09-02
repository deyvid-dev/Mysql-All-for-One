# Projeto Mysql-All-for-One

## 📁 Sobre

Projeto desenvolvido na Trybe durante o curso de Desenvolvimento Web.

Este projeto consiste em realizar desafios para praticar conceitos de SQL.

## :rocket: Tecnologias utilizadas

- Git
- MySQL
- MySQL Workbench
- VsCode

## 📌 Requisitos do projeto

### Desafios Iniciais

<details>
  <summary>Desafio 1</summary>
  <br>
  
1 - Exibe apenas os nomes dos produtos na tabela `products`.
</details>

<details>
  <summary>Desafio 2</summary>
  <br>
  
2 - Exibe os dados de todas as colunas da tabela `products`.
</details>

<details>
  <summary>Desafio 3</summary>
  <br>
  
3 - Exibe os valores da coluna que representa a primary key da tabela `products`.
</details>
  
<details>
  <summary>Desafio 4</summary>
  <br>
  
4 - Exibe quantos registros existem na coluna product_name da tabela `products`.
</details>
  
<details>
  <summary>Desafio 5</summary>
  <br>
  
5 - Exibe os dados da tabela `products` a partir do quarto registro até o décimo terceiro.

 - Observações técnicas
 
   - Tanto o quarto quanto o décimo terceiro registros, precisam aparecer na consulta;
   
   - Não use `where` ou `order by`.
</details>
  
<details>
  <summary>Desafio 6</summary>
  <br>
  
6 - Exibe os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.
</details>
  
<details>
  <summary>Desafio 7</summary>
  <br>
  
7 - Mostra apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).
</details>
  
<details>
  <summary>Desafio 8</summary>
  <br>
  
8 - Retorna três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.

 - Observações técnicas

   - Na primeira coluna, exiba a soma de `5 + 6` (essa soma deve ser realizada pelo SQL);

   - Na segunda coluna deve haver a palavra "de";

   - E por fim, na terceira coluna, exiba a soma de `2 + 8` (essa soma deve ser realizada pelo SQL);

   - A primeira coluna deve se chamar "A", a segunda coluna deve se chamar "Trybe" e a terceira coluna deve se chamar "eh";

   - Não use colunas pré-existentes, apenas o que for criado na hora.
</details>
  
### Desafios sobre filtragem de dados
  
<details>
  <summary>Desafio 9</summary>
  <br>
  
9 - Mostra todos os valores de `notes` da tabela `purchase_orders` que não são nulos.
</details>
  
<details>
  <summary>Desafio 10</summary>
  <br>
  
10 - Mostra todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.

 - Observações técnicas

   - Como critério de desempate para a ordenação, ordene também os resultados pelo `id` de forma crescente.
</details>
  
<details>
  <summary>Desafio 11</summary>
  <br>
  
11 - Exiba os dados da coluna notes da tabela `purchase_orders` em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39.
</details>
  
<details>
  <summary>Desafio 12</summary>
  <br>
  
12 - Mostra as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.
</details>
  
<details>
  <summary>Desafio 13</summary>
  <br>
  
13 - Mostra o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.
</details>
  
<details>
  <summary>Desafio 14</summary>
  <br>
  
14 - Mostra os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3.
</details>
  
<details>
  <summary>Desafio 15</summary>
  <br>
  
15 - Mostra somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.

  - Observações técnicas
  
    - Chame essa coluna de `submitted_hour`.
</details>

<details>
  <summary>Desafio 16</summary>
  <br>
  
16 - Exibe a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.
</details>
  
<details>
  <summary>Desafio 17</summary>
  <br>
  
17 - Mostra os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.
</details>
  
<details>
  <summary>Desafio 18</summary>
  <br>
  
18 - Mostra todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.
</details>
  
<details>
  <summary>Desafio 19</summary>
  <br>
  
19 - Mostra a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.

  - Observações técnicas

    - Chama a coluna de `orders_count`.

### Desafios de manipulação de tabelas
</details>
  
<details>
  <summary>Desafio 20</summary>
  <br>
  
20 - Adicione à tabela `order_details` um registro com order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129.

  - Observações técnicas
  
    - Obs.: o id deve ser incrementado automaticamente.
</details>
  
<details>
  <summary>Desafio 21</summary>
  <br>
  
21 - Adicione com um único INSERT, duas linhas à tabela order_details com os mesmos dados do requisito 20.

  - Observações técnicas
  
    - Esses dados são novamente order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129;

    - O ìd deve ser incrementado automaticamente.
</details>
  
<details>
  <summary>Desafio 22</summary>
  <br>
  
22 - Atualize os dados de discount do order_details para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).
</details>
  
<details>
  <summary>Desafio 23</summary>
  <br>
  
23 - Atualize os dados da coluna discount da tabela order_details para 30, onde o valor na coluna unit_price seja menor que 10.0000.

  - Observações técnicas

    - Não é necessário utilizar o SAFE UPDATE em sua query.
</details>
  
<details>
  <summary>Desafio 24</summary>
  <br>
  
24 - Atualize os dados da coluna discount da tabela order_details para 45, onde o valor na coluna unit_price seja maior que 10.0000 e o id seja um número entre 30 e 40.

  - Observações técnicas
    - Não é necessário utilizar o SAFE UPDATE em sua query.
</details>
  
<details>
  <summary>Desafio 25</summary>
  <br>
  
25 - Delete todos os dados em que a unit_price da tabela order_details seja menor que 10.0000.
</details>
  
<details>
  <summary>Desafio 26</summary>
  <br>
  
26 - Delete todos os dados em que a unit_price da tabela order_details seja maior que 10.0000.
</details>
  
<details>
  <summary>Desafio 27</summary>
  <br>
  
27 - Delete todos os dados da tabela order_details.
</details>

![Badge finalizado](http://img.shields.io/static/v1?label=STATUS&message=Finalizado&color=GREEN&style=for-the-badge)

---------------------------------------

Desenvolvido por Deyvid Cavalcante.
