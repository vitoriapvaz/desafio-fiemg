# desafio-fiemg

# falcon9-routines


<!--ts-->
- [Sobre](#sobre)
  - [Instalar dependências](#instalar-dependências)
- [Dicionário de Dados](#dicionário-de-dados)

<!--te-->

Sobre
====
Este projeto tem como objetivo resolver problemas de inconsistências de dados em um marketplace B2B, utilizando SQL para gerar análises confiáveis que suportem decisões de negócio.

Instalar dependências
----
```bash
pip install pandasql
```

Dicionário de Dados
====

| Tabela                   | Descrição                                     |
|------------------------|-----------------------------------------------|
| orders     | Pedidos realizados                       |
| order_items     | Itens de cada pedido                       |
| products     | Catálogo de produtos                       |
| sellers     | Distribuidoras vendedoras                       |
| buyers     | Supermercados compradores                       |
| payments     | Registro de pagamentos                       |