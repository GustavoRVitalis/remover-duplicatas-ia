# README.md

# Remover Duplicados em Listas Python

Este projeto apresenta uma função simples em Python para remover elementos duplicados de listas, preservando a ordem original dos itens.

## Como funciona

A função [`remover_duplicados`](main.py) utiliza um dicionário para eliminar duplicatas de qualquer lista (números, strings, etc.), mantendo apenas a primeira ocorrência de cada elemento.

## Exemplo de uso

Veja exemplos de uso no arquivo [main.py](main.py):

```python
lista = [1, 2, 2, 3, 4, 4, 5]
print(remover_duplicados(lista))   # Saída: [1, 2, 3, 4, 5]

nomes = ["Ana", "João", "Ana", "Maria", "João"]
print(remover_duplicados(nomes))   # Saída: ['Ana', 'João', 'Maria']
```

## Como executar

1. Certifique-se de ter o Python instalado.
2. Execute o arquivo principal:

```sh
python main.py
```

Conversa com o github Copilot

- Faça uma função que remova duplicações de um array

- nessa funcao adicione mais 3 listas com nomes, raça de cachorro e letras e mostre tudo

- agr crie um readme.mo sobre esse projeto para publicacao no github

- Read.me criado e otimo modelo de Prompt criado
