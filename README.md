# Projeto: Algoritmos de Criptografia em C++

## Descrição

Este projeto é uma aplicação em C++ que implementa diferentes técnicas de criptografia baseadas em transposição e cifra por colunas.

O programa permite ao usuário criptografar e descriptografar mensagens utilizando dois métodos principais:

* Cifra por colunas
* Transposição com chave

A aplicação é executada via terminal e possui um menu interativo para seleção das operações.

---

## Funcionalidades

* Criptografia utilizando cifra por colunas
* Descriptografia utilizando cifra por colunas
* Criptografia por transposição com chave
* Descriptografia por transposição com chave
* Menu interativo para múltiplas operações
* Manipulação de strings e matrizes para transformação dos dados

---

## Tecnologias Utilizadas

* C++
* Biblioteca padrão (`iostream`, `cstring`, `string`)

---

## Estrutura do Projeto

```id="z7m2xp"
📁 projeto
└── main.cpp
```

---

## Como Compilar e Executar

1. Compile o código:

```bash id="k8x3mn"
g++ main.cpp -o programa
```

2. Execute:

```bash id="p2v9ql"
./programa
```

---

## Exemplo de Uso

```id="t4n6yx"
Algoritmos de Criptografia --- Criptografar e Descriptografar
1 - Criptografar cifra das Colunas
2 - Descriptografar cifra das Colunas
3 - Criptografar por Transposicao
4 - Descriptografar por Transposicao
0 - Sair

Digite uma opcao: 3
Digite a Chave: 3
Digite a Mensagem: HELLO

Saída: HLOELX
```

---

## Como Funcionam os Métodos

### Cifra por Colunas

* A mensagem é organizada em uma matriz com número de colunas definido pelo usuário
* A leitura da matriz ocorre por colunas, gerando o texto criptografado
* Para descriptografar, o processo é invertido

### Transposição com Chave

* A mensagem é distribuída em uma matriz com base na chave
* Caracteres extras podem ser preenchidos com `X`
* A leitura em ordem diferente gera a criptografia
* A descriptografia reorganiza os dados na ordem original


