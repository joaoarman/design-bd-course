# Curso de Modelagem de Dados


## Passos para a Modelagem:

1. Entender e pensar no software que será desenvolvido;
2. Anotar ideias e funcionalidades;
3. Levantar requisitos com o(s) cliente(s);
4. Entender e analisar melhor o que deverá ser feito;
5. Partir para a modelagem de dados. As etapas são dividias em:
    1. **CONCEITUAL**: onde são definidas as **principais** entidades do projeto (tabelas);
    2. **LÓGICO**: onde são definidos os principais **atributos** de cada entidade (colunas);
    3. **FÍSICO**: a etapa física é quando a modelagem está pronta. A transição da etapa lógica para a física é um processo que chamamos de normalização, que é dívido por partes:
        1. N1:
        2. N2:
        3. N3:



## Requisitos:

A Coral Store é uma pequena livraria de bairro, o dono nos contratou para desenvolver um e-commerce para sua empresa

A ideia central é captar os dados dos **clientes**, eles são: nome, email, senha, endereço e telefone.

O sistema também precisa possibilitar cadastrar os **produtos**, como vendemos apenas livros o site a princípio não terá categorias.

Os produtos precisam conter: nome, preço, descrição, número de páginas e ISBN.

Precisamos também salvar as **compras de cada usuário**, que deve conter: o valor total e itens comprados.

Este será o MVP da Coral Store, se o projeto der certo seremos contratados para expandir o mesmo.


## Novos Requisitos no caminho:

* Surgiu a necessidade de um campo que indique se o produto está ou não disponível no estoque
* O usuário pode ter mais de um endereço (relação 1:n)
* Todo o pedido precisa conter um endereço de entrega
* Adicionar colunas de pedido criado e pedido entregue na tabela de pedidos