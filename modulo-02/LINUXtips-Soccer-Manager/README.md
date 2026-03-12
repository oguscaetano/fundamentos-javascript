# ⚽️ Xablau Soccer Manager

Neste projeto você colocará em prática os conhecimentos de lógica de programação com JavaScript, focando em manipulação de arrays e iterações complexas.

<div align="center">
  <img src="./pinguim-coach.png" alt="drawing" width="300"/>
  <p>Tux Coach</p>
</div>

## Conceitos Praticados

- Loop `for` e iterações em arrays
- Loops aninhados para percorrer sub-estruturas
- Manipulação de arrays de strings
- Uso de métodos como `push()` e `includes()`
- Tratamento de dados e geração de relatórios

## Requisitos

Para resolver os requisitos, utilize o seu respectivo arquivo, disponíveis na raiz deste projeto.

### 1 - Relatório de nacionalidades únicas

Desenvolva um algoritmo que percorra todas as strings do array `nacionalidades`. Você deve criar um array vazio chamado `paisesUnicos`. Para cada país encontrado, verifique se ele já está no novo array. Se não estiver, adicione-o.

> O array `paisesUnicos` não deve possuir nenhum nome de país repetido.

---

### 2 - Verificar patrocinador

Crie uma lógica que verifique se o "Real Madrid" possui o patrocinador "Adidas". Utilize o array `patrocinadores` e o método **includes**. O resultado deve ser exibido no console como um valor booleano.

> 💡 Teste diferentes nomes de patrocinadores para diferentes clubes.

---

### 3 - Contratação de reforço

Simule a entrada de um novo jogador no Barcelona. Adicione o nome "Romario" ao array `jogadoresPorTime` e a lista de habilidades `["Drible", "Agilidade", "Molejo"]` ao array `habilidadesPorJogador`.

---

### 4 - Contagem de jogadores por time

Gere um relatório com a quantidade de jogadores por cada clube.
Exemplo de saída esperada:

```js
[
  ["Real Madrid: 3"],
  ["Barcelona: 4"],
  ["Corinthians: 17"],
  ...
]
```

---

### 5 - Adição de patrocinador

A Xablau quer entrar para o ramo futebolístico e resolveu patrocinar vários clubes. Adicione a Xablau como patrocinadora de todos os times disponíveis.
Após adicionar, exiba na tela o nome do time e quais são seus patrocinadores.
Exiba da seguinte forma:

```js
[
  "Patrocinadores do Real Madrid: Emirates, Adidas, HP, Xablau",
  "Patrocinadores do Barcelona: Nike, Spotify, Beko, Xablau",
  ...
]
```

> 💡 Pesquise pelo método `join()` 😉

---

### 6 - Localizar jogador por habilidade

Crie um algoritmo que percorra todo o array `habilidadesPorJogador` usando **loops aninhados** (um para times e outro para jogadores). Use o método **includes** para verificar se a string "Drible" está presente. Se estiver, dê um **push** do nome do jogador (encontrado via índice no array `jogadoresPorTime`) em uma nova lista chamada `listaDribladores`.

Saída esperada:

```js
[
  'Zinedine Zidane',
  'Ronaldo Fenomeno',
  'Ronaldinho Gaucho',
  'Rivelino',
  'Marcelinho Carioca',
  'Kaka',
  'Adriano'
]
```

---

### 7 - Todos contra todos

Crie um algoritmo que gere chaveamento de jogos entre os times seguindo as seguintes regras:

- Todos os times jogam contra todos
- Nenhum time pode jogar contra ele mesmo
- Não pode haver confronto duplicado (se já existe "Real Madrid x Barcelona", não pode existir "Barcelona x Real Madrid")

Exiba o resultado da seguinte forma:

```js
[
  "Real Madrid x Barcelona",
  "Real Madrid x Milan",
  "Barcelona x Milan"
  ...
]
```

Também exiba a quantidade de jogos.

> 💡 A quantidade de jogos segue a fórmula: `(n * (n - 1)) / 2`, onde `n` é a quantidade de times.

---

### 8 - Campeonato

Desenvolva um algoritmo de campeonato seguindo as seguintes regras:

- Todos os times jogam contra todos (da mesma forma que o requisito anterior)
- Simular placar aleatório (entre `0` e `5` gols para cada time)
- Cada vitória soma 3 pontos ao time vencedor
- Empate soma 1 ponto para os dois times
- O time perdedor não recebe nenhum ponto

Você deverá exibir os resultados dos jogos, a tabela de pontos e o time que foi o grande campeão.

Exiba os resultados no seguinte formato:

```js
=== RESULTADOS DOS JOGOS ===
[
  'Real Madrid 0 x 2 Barcelona',
  'Real Madrid 4 x 4 Corinthians',
  'Real Madrid 1 x 1 Milan',
  'Real Madrid 3 x 4 Inter de Milao',
  'Barcelona 0 x 4 Corinthians',
  'Barcelona 5 x 2 Milan',
  'Barcelona 5 x 0 Inter de Milao',
  'Corinthians 5 x 2 Milan',
  'Corinthians 5 x 3 Inter de Milao',
  'Milan 4 x 4 Inter de Milao'
]

=== TABELA DE PONTOS ===
Real Madrid: 2
Barcelona: 9
Corinthians: 10
Milan: 2
Inter de Milao: 4

CAMPEÃO: Corinthians com 10 pontos!
```
