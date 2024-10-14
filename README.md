# Desafio de Integração – XML e JSON

Este repositório contém a modelagem de dados em XML e JSON para um exemplo de produtos de uma loja virtual. O objetivo deste desafio é demonstrar o entendimento sobre diferentes formatos de payload e como representá-los.

## Estruturas de Dados

### XML

```xml
<produtos>
  <produto>
    <id>1</id>
    <nome>Camisa Polo</nome>
    <descricao>Camisa polo de algodão</descricao>
    <preco>59.90</preco>
    <categoria>Roupas</categoria>
    <estoque>100</estoque>
  </produto>
</produtos>
```

### JSON

```json
[
  {
    "id": "1",
    "nome": "Camisa Polo",
    "descricao": "Camisa polo de algodão",
    "preco": 59.90,
    "categoria": "Roupas",
    "estoque": 100
  }
]
```
