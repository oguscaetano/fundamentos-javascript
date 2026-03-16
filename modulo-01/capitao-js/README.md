# Capitão JS

Você é o `Capitão JS` da **Liga JS**, uma equipe de super-heróis que usa JavaScript pra salvar o mundo.
Cada requisito é uma missão.

<div align="center">
  <img src="./capitao-js.jpeg" alt="drawing" width="300"/>
  <p>Capitão JS (o brabo)</p>
</div>

## Conceitos Praticados

- Variáveis
- Tipos de dados
- Operações aritméticas
- Operadores condicionais
- Estruturas condicionais
- Operadores lógicos
- Strings

## Requisitos

### 1 — O Recruta

Crie as informações básicas de um herói: nome, idade, se ele é humano e seu poder inicial. Exiba essas informações no `console`.

---

### 2 — O Codinome Secreto

Todo herói tem um codinome que **não pode mudar**. Crie o codinome e o nível inicial do herói (número inteiro).

---

### 3 — Energia de Combate

O herói começa com 100 de energia.
Ele luta contra dois vilões e perde 25 de energia em cada luta.
Calcule a energia restante.

Formato da saída:

```js
"Energia restante:", energia
```

---

### 4 — Golpe Crítico

O dano base do herói é 10.
Um golpe crítico dobra o dano e soma 5 de bônus.
Calcule o dano final corretamente.

---

### 5 — O Julgamento da Liga

Se o herói tiver energia maior ou igual a 50, ele pode continuar na missão.
Caso contrário, deve recuar.

---

### 6 — A Avaliação Suprema

Se o nível do herói for:

- menor que 5 → recruta
- entre 5 e 9 → veterano
- 10 ou mais → lendário

---

### 7 — Aliança de Heróis

O herói só entra na batalha final se:

- tiver energia maior que 60 **E**
- for veterano ou lendário

> Utilize o código do requisito anterior como base.

---

### 8 — O Detector de Energia

Crie um algoritmo que identifica se a energia do herói é par ou ímpar.

---

### 9 — Escolha do Poder

Crie um algoritmo que dependendo do elemento escolhido, o herói recebe um poder diferente:

- fogo → Chamas infinitas
- gelo → Congelamento absoluto
- raio → Choque do trovão
- sombra → Invisibilidade

---

### 10 — Identidade do Herói

Crie variáveis que recebem valores para `nome`, `codinome` e `poder`.
Depois exiba uma frase juntando os valores dessas variáveis.

Exemplo:

```js
"Eu sou " + nome + ", conhecido como " + codinome + ", e meu poder é " + poder + "."
```

---

### 🔥 BÔNUS — A BATALHA FINAL

Crie um algoritmo para nosso herói que:

- tenha nome, codinome, energia, nível, elemento
- calcule dano baseado no nível
- verifique se a energia é par ou ímpar
- decida se entra ou não na batalha final (se a energia for maior que 60 e o nível maior ou igual a 5 o herói pode entrar na batalha final)
- mostre uma mensagem final épica no formato:

```js
console.log(`${nome} (${codinome}), entrou na batalha final!
  Poder: ${poder}
  Dano: ${danoFinal}
  Energia: ${energia} (${energiaTipo}).`);
```

> 1. Utilize requisitos anteriores como base para fazer esse.
> 2. Caso o herói não entre na batalha, exiba: "Herói não está pronto para a batalha final."
