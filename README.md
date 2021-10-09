# Git playground

* Clone the repo
* Create branch to work (always from master)
* Work finished push the commits and create PR to master


## Create a file index.js

```javascript
function suma(a, b) {
  return a + b;
}

function resta(a, b) {
  return a - b;
}

function multiplicacion(a, b) {
  return a * b;
}

function division(a, b) {
  return a * b;
}

function addedPokedexDetail(pokemons) {
  return pokemons.map((item) => {
    return {
      id: item.id,
      name: item.name,
      detail: `https://pokeapi.co/api/v2/pokemon/${item.id}`
    };
  });
}

const suma1 = suma(1, 2);
const suma2 = suma(10, 2);
const suma3 = suma(12, 24);

console.log("suma1 =>", suma1);
console.log("suma2 =>", suma2);
console.log("suma3 =>", suma3);

const resta1 = resta(1, 2);
const resta2 = resta(10, 2);
const resta3 = resta(12, 24);

console.log("resta1 =>", resta1);
console.log("resta2 =>", resta2);
console.log("resta3 =>", resta3);

const multiplicacion1 = multiplicacion(1, 2);
const multiplicacion2 = multiplicacion(10, 2);
const multiplicacion3 = multiplicacion(12, 24);

console.log("multiplicacion1 =>", multiplicacion1);
console.log("multiplicacion2 =>", multiplicacion2);
console.log("multiplicacion3 =>", multiplicacion3);

const division1 = division(1, 2);
const division2 = division(10, 2);
const division3 = division(12, 24);

console.log("division1 =>", division1);
console.log("division2 =>", division2);
console.log("division3 =>", division3);

const pokedex = [
  { name: "bulbasaur", id: 1 },
  { name: "ivysaur", id: 2 },
  { name: "venusaur", id: 3 },
  { name: "charmander", id: 4 },
  { name: "charmeleon", id: 5 }
];

const pokedexWithDetail = addedPokedexDetail(pokedex);

console.log("pokedexWithDetail =>", pokedexWithDetail);

```

##  Create index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <h1>Hola Mundo!</h1>
</body>
</html>
```

##  Create styles.css

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  background: gray;
}

h1 {
  color: red;
}
```