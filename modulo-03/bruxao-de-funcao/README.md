# 🧙‍♂️ Bruxão de Função

Neste projeto você colocará em prática os conhecimentos de **funções em JavaScript**.

O objetivo é resolver desafios usando **funções, loops e manipulação de arrays**, simulando situações do dia a dia de dev.

<div align="center">
  <img src="./mago-xablau.png" alt="drawing" width="300"/>
  <p>O mago Xablau</p>
</div>

O objetivo deste projeto é colocar em prática os conhecimentos adquiridos de:

- Funções
- Manipulação de arrays
- Uso de loops for
- Uso de condicionais if / else
- Manipulação de strings, números e booleanos
- Uso de push()

> Utilize o arquivo `resolucao.js` para resolver os requisitos do projeto.

---

## Requisitos

### 1 - Criar função de saudação mágica

Crie uma função chamada `saudacaoMago` que recebe o nome do aluno como parâmetro.

Ela deve retornar a frase:

```js
Boas-vindas à Escola Xablau de Magia, {NOME}!
```

>Teste a função com pelo menos 3 nomes de alunos diferentes.

---

### 2 - Função para listar alunos

Crie uma função chamada `listarAlunos`. Ela deve percorrer o array `alunos` e exibir todos os nomes no console.

---

### 3 - Função para contar alunos

Crie uma função chamada `contarAlunos`. Ela deve retornar quantos alunos existem no array.

Exemplo de saída:

```js
Total de alunos: 5
```

---

### 4 - Criar função que retorna a casa do aluno

Crie uma função chamada `obterCasaDoAluno` que deve receber o `nome` do aluno como parâmetro. Ela deve procurar o aluno no array `alunos` e retornar a casa correspondente no array `casasAlunos`.

Exemplo:

```js
Hermione pertence à casa Grifinoria
```

---

### 5 - Função para adicionar novo aluno

Crie uma função chamada `adicionarAluno`.

Ela deve:

- receber o nome do aluno como parâmetro
- receber a casa como parâmetro
- dar push no array `alunos`
- dar push no array `casasAlunos`

Após todo o processo ter sido finalizado, exibir a seguinte mensagem:

```js
{NOME} adicionado(a) com sucesso na casa {NOMECASA}.
```

---

### 6 - Criar lista de todos os feitiços únicos

Crie uma função chamada `listarFeiticosUnicos`. Ela deve:

- percorrer todos os feitiços
- criar um array `feiticosUnicos`
- adicionar apenas feitiços que não se repetem na lista

---

### 7 - Função que conta quantos alunos existem por casa

Crie uma função chamada `contarAlunosPorCasa`.

Ela deve retornar a quantidade de alunos por cada casa.
O retorno deve ser no formato:

```js
[
  "Grifinoria = 19",
  "Sonserina = 5",
  "Corvinal = 6",
  "Lufa-Lufa = 6"
]
```

---

### 8 - Função para dar pontos para as casas

Crie uma função chamada `adicionarPontos`. Ela deve adicionar pontos para cada casa. Os pontos devem ser aleatórios, sendo números inteiros de 0 a 100. Utilize o array `pontosDasCasas`.

Exemplo de saída da função:

```js
[
  ["Grifinoria", 10], 
  ["Sonserina", 89], 
  ["Corvinal", 22], 
  ["Lufa-Lufa", 97]
]
```

---

### 9 - Função que exibe ranking das casas

Crie uma função chamada `mostrarRanking` que exibe em ordem decrescente o ranking das casas com base nos pontos. A função deve "chamar" a função `adicionarPontos` para que gere os pontos para fazer a ordenação.

Exemplo de saída:

```js
[
  ["Lufa-Lufa", 97],
  ["Sonserina", 89], 
  ["Corvinal", 22], 
  ["Grifinoria", 10] 
]
```

---

### 10 - Criar lista de alunos por casa

Crie uma função chamada `alunosPorCasa` que recebe o nome da casa como parâmetro. Ela deve retornar um array com todos os nomes dos alunos daquela casa.

---

### Desafio Extra

Crie uma função chamda `criarAlunoAleatorio`.

Ela deve:

- adicionar um nome no array `nomes`
- atribuir uma casa aleatória no array `casasAlunos`
- retornar o nome e casa do novo aluno no formato: "{NOME} adicionado na casa {NOMECASA}"
