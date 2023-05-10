# MÉTODOS ARRAY
>[MDN WEB DOC](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)

```js
//Array:
let minhaArray = ['banana', 'abacaxi', 'laranja', 'maçã', 'uva'];
```
-	## Listar: for ou forEach

### Usando o "for" para acessar cada item da Array.
```js
for (let i = 0; i < minhaArray.length; i++) {
  console.log(minhaArray[i]);
}
```
### Ou pode-se usar o "forEach" para acessar cada item da Array.
```js
minhaArray.forEach(function(minhaArray) {
   console.log(minhaArray);
});
```
-	## Listar em ordem alfabética: sort
```js
minhaArray.sort();

for (let i = 0; i < minhaArray.length; i++) {
  console.log(minhaArray[i]);
}
```
-	## Adicionar (ultimo): push
```js
minhaArray.push('melancia');
console.log(minhaArray);
```
-	## Adicionar (index): splice

### No index (2), removendo (0) itens, adiciona o item ('kiwi').
```js
minhaArray.splice(2, 0, 'kiwi');
console.log(minhaArray);
```
-	## Remover (ultimo): pop
```js
let removeFim = minhaArray.pop();
console.log(minhaArray);
```
-	## Remover (index): splice

### Remove do indice (2) apenas (1) item.
```js
minhaArray.splice(2, 1);
console.log(minhaArray);
```
-	## Separar: slice
```js
let i
let primeiraMetade = minhaArray.slice(0, 2);
let segundaMetade = minhaArray.slice(2, i);

console.log(primeiraMetade);
console.log(segundaMetade);
```
-	## Juntar Arrays: concat
```js
let minhaArray = primeiraArray.concat(segundaArray);
console.log(minhaArray);
```
-	## Converter em String:
```js

```
-	## Inverter Ordem:
```js

```
-	## Confirmar Elemento:
```js

```

