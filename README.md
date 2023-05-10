# MÉTODOS ARRAY
>[MDN WEB DOC](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)

```js
//Array:
let minhaArray = ['banana', 'abacaxi', 'laranja', 'maçã', 'uva'];
```
-	## Listar:

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
-	## Listar em ordem alfabética:
```js
minhaArray.sort();

for (let i = 0; i < minhaArray.length; i++) {
  console.log(minhaArray[i]);
}
```
-	## Adicionar (ultimo):
```js
minhaArray.push('melancia');
console.log(minhaArray);
```
-	## Adicionar (index):

### No index (2), removendo (0) itens, adiciona o item ('kiwi').
```js
minhaArray.splice(2, 0, 'kiwi');
console.log(minhaArray);
```
-	## Remover (ultimo):
```js
let removeFim = minhaArray.pop();
console.log(minhaArray);
```
-	## Remover (index) -

### Remove do indice (2) apenas (1) item.
```js
minhaArray.splice(2, 1);
console.log(minhaArray);
```
-	## Separar - 
```js

```
-	## Juntar Arrays -  
-	## Converter em String - 
-	## Inverter Ordem - 
-	## Confirmar Elemento - 
