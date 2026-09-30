# Wikipedia Clone

Clone da página inicial da Wikipédia, feito para estudar **HTML5 semântico** — a
estrutura de um documento real, não de um layout.

## O que treina

Um layout visual é fácil: qualquer `<div>` posicionada resolve. O exercício aqui é o
outro — **escolher a tag certa**:

| Tag | Por que |
| :--- | :--- |
| `<header>` | cabeçalho do documento, não do site |
| `<nav>` | navegação principal, para leitores de tela |
| `<main>` | o conteúdo único da página |
| `<section>` | divisão temática com título próprio |
| `<h1>`–`<h2>` | hierarquia de títulos, base da navegação por teclado |

A regra que a maioria ignora: a hierarquia de títulos precisa ser **contínua e
sem pulos**. `h1` → `h2` → `h3`, nunca `h1` → `h3`. É isso que permite a alguém
navegar a página por Cabeçalhos sem ler nada.

A mesma página, com CSS puramente decorativo — cor, espaçamento, grid. Nenhuma
posição absoluta, nenhum `z-index` para "consertar" o fluxo.

## Estrutura

```
index.html    documento único: marcação semântica + CSS embutido
```

Sem JavaScript, sem dependências, sem build.

## Como rodar

Abra o `index.html` no navegador — funciona direto do disco, sem servidor.

## Licença

MIT
