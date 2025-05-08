# Aula 5

- Relacionamento no contexto de BI (Business Intelligence), o relacionamento entre tabelas é um conceito fundamental que permite integrar dados de diferentes fontes ou tabelas de maneira lógica e coerente. Ele funciona de forma parecida com os relacionamentos em bancos de dados relacionais.

### Tipos comuns de relacionamento:
- Um-para-muitos (1:N)

Exemplo: Uma tabela de clientes (1) se relaciona com uma tabela de vendas (N), pois um cliente pode ter várias vendas.

- Muitos-para-um (N:1)

Inverso do anterior; ocorre quando você navega de muitas vendas para um cliente.

- Muitos-para-muitos (N:N)

Exemplo: Produtos e pedidos (um produto pode estar em vários pedidos, e um pedido pode ter vários produtos).

Em ferramentas como Power BI, esse tipo exige tabelas intermediárias ou configurações especiais.

- Um-para-um (1:1)

Menos comum, mas pode ocorrer quando duas tabelas compartilham uma chave única entre si.

## Por que isso é importante?
Permite cruzar dados de diferentes tabelas (fatos e dimensões).

Garante que os filtros aplicados em relatórios sejam propagados corretamente.

Evita duplicidade ou perda de dados nas análises.