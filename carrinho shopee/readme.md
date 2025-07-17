# 🛒 Carrinho Shopee

Simulação de um carrinho de compras com funcionalidades inspiradas na plataforma Shopee. O projeto tem como objetivo **reforçar conceitos de arrays, funções, promessas (Promises) e manipulação de dados em JavaScript**, utilizando práticas modernas e exemplos próximos ao mundo real.

---

## 🎯 Objetivo

- Adicionar e remover **itens de compra**
- Gerenciar um **carrinho com itens escolhidos**
- Trabalhar com **listas**, **funções auxiliares** e **operações comuns com arrays**

---

## 🧠 Anotações de Estudo

Este projeto foi criado com foco em aprendizado. Abaixo estão alguns conceitos importantes usados durante o desenvolvimento:

### 📌 Operações com Arrays

- `push` – Adiciona um item ao **final** do array
- `shift` – Remove o **primeiro** item do array
- `pop` – Remove o **último** item do array
- `reduce` – Reduz um array a um único valor (ex: total do carrinho)
- `indexOf` – Retorna o **índice** de um item no array
- `splice` – Remove um ou mais itens do array por índice
- `findIndex` – Encontra o **índice** de um item com base em uma condição
- `forEach` – Percorre cada item do array

### 🧮 Trabalhando com valores

- O `0` como argumento inicial em `reduce` define o valor de partida da operação (ex: total = 0)
- Template strings com `${}` permitem embutir variáveis e expressões diretamente no texto

### ⏳ Promessas e `async/await`

- `await` é usado para aguardar a resolução de uma Promise antes de continuar
- Se a operação não depende de uma promessa, **não é necessário usar `await`**
- Para usar `await`, a função deve ser marcada como `async`

---

## 💡 Possível expansão

- Criar uma **lista de desejos** (wishlist) usando a mesma lógica do carrinho:
```js
cartService.addItemToCart(Wishlist, item);
