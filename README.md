# 📊 Sistema de Manipulação de Grafos em C

## 📖 Descrição

Este projeto implementa um sistema simples para manipulação de grafos não direcionados utilizando a linguagem C e representação por matriz de adjacência.

O programa permite criar um grafo, adicionar e remover arestas, visualizar a matriz de adjacência, calcular o grau dos vértices e listar suas adjacências por meio de um menu interativo no terminal.

---

## 🚀 Funcionalidades

- Limpar o grafo
- Adicionar arestas
- Remover arestas
- Exibir matriz de adjacência
- Calcular o grau dos vértices
- Exibir lista de adjacências
- Menu interativo para gerenciamento do grafo

---

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Biblioteca padrão:
  - stdio.h
  - stdlib.h

---

## 📐 Estrutura do Grafo

O grafo é representado por uma matriz de adjacência:

```c
int graph[MAX_VERTICES][MAX_VERTICES];
```

Onde:

- `graph[i][j] = 1` indica uma aresta entre os vértices `i` e `j`;
- `graph[i][j] = 0` indica ausência de conexão.

O sistema utiliza grafos não direcionados, portanto:

```c
graph[origem][destino] = 1;
graph[destino][origem] = 1;
```

---

## 📋 Menu do Programa

```text
MENU DO GRAFO

1 - Limpar grafo
2 - Inserir/remover aresta
3 - Mostrar matriz
4 - Mostrar graus
5 - Mostrar adjacências
6 - Sair
```

---

## ▶️ Como Executar

### Compilar

```bash
gcc grafo.c -o grafo
```

### Executar

```bash
./grafo
```

No Windows:

```bash
grafo.exe
```

---

## 💻 Exemplo de Uso

Entrada:

```text
Quantidade de vértices: 4

Adicionar aresta:
Origem: 0
Destino: 1
```

Saída:

```text
Matriz de adjacência

     0 1 2 3
0 |  0 1 0 0
1 |  1 0 0 0
2 |  0 0 0 0
3 |  0 0 0 0
```

---

## 📚 Conceitos Aplicados

- Estrutura de Dados
- Grafos
- Matriz de Adjacência
- Grau de Vértice
- Lista de Adjacências
- Algoritmos Básicos em Grafos
- Programação em C

---

## 🎓 Objetivo Acadêmico

Este projeto foi desenvolvido para fins de estudo da disciplina de Estrutura de Dados, com foco na representação e manipulação de grafos utilizando matriz de adjacência.

---
