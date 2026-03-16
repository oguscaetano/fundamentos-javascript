# Poke CLI

<div align="center">
  <img src="./pikaxuxu.jpg" alt="drawing" width="300"/>
  <p>O Pikaxuxu diz "Oi".</p>
</div>

O objetivo deste projeto é colocar em prática os conhecimentos adquiridos em todo o curso.

---

## API utilizada

Você utilizará a **PokeAPI**

[https://pokeapi.co/](https://pokeapi.co/)

Exemplo de chamada:

[https://pokeapi.co/api/v2/pokemon/pikachu](https://pokeapi.co/api/v2/pokemon/pikachu)

>Todas as saídas dos requisitos devem ser no console, utilizando o conceito de CLI (Command-line Interface).

---

## Requisitos

### 1. Buscar um Pokémon pelo nome ou ID

Crie uma função chamada `getPokemon` que receba o **nome de um pokémon** ou seu **ID** e retorne os dados dele usando `fetch`.

Caso o Pokémon **não exista**, trate o erro retornando a mensagem:

```js
Erro: Pokémon não encontrado
```

---

### 2. Exibir nome e ID do Pokémon

Crie uma função chamada `getPokemonNameId` que utiliza a função `getPokemon` mas exibe apenas o ID e nome do pokémon no seguinte formato:

```js
#25 - Pikachu
```

---

### 3. Exibir altura e peso

Crie uma função chamada `getPokemonInfo` que retorne os seguintes dados:

- Nome
- ID
- Altura
- Peso

Exemplo de saída:

```js
#25 - Pikachu
Altura: 4
Peso: 60
```

---

### 4. Listar os tipos do Pokémon

Crie uma função que retorna todos os tipos de um determinado Pokémon.

Exemplo de saída:

```js
#1 - Bulbasaur
Tipos: grass, poison
```

---

### 5. Buscar vários pokémons

Crie uma função que receba **um array de IDs** e busque todos os pokémons. O array recebido pode ter quantidade de elementos diferentes.

Exemplo de chamada da função:

```js
getPokemons([25, 4, 35])
```

Saída esperada:

```js
Pikachu, Charmander, Clefairy
```

>💡 Dica: Pesquise sobre `Promise.All()`.

---

### 6. Filtrar pokémons por tipo

Retorne apenas pokémons que possuam determinado tipo.

Exemplo:

```js
filterByType("fire")
```

---

### 7. Ordenar pokémons por peso

Ordene do **mais pesado para o mais leve**. Exiba apenas os 5 mais pesados.

Exemplo de saída:

```js
Snorlax - 4600
Charizard - 905
Pikachu - 60
...
```

---

### 8. Criar um objeto agrupado por tipo

Crie um objeto que separa os pokémons por tipo. Cada tipo deve ser uma propriedade que tem como valor um array com todos os nomes de pokémons daquele respectivo tipo.
Faça isso levando em conta apenas os 150 primeiros pokémons (de ID = 0 até 150).

```js
{
  electric: ["pikachu", "raichu"],
  fire: ["charmander", "vulpix"],
  water: ["squirtle"]
  ...
}
```
