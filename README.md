# MÉTODOS ARRAY
>[MDN WEB DOC](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)

//Array:
let minhaArray = ['banana', 'abacaxi', 'laranja', 'maçã', 'uva'];

-	## Listar -

### Usando o "for" para acessar cada item da Array.

for (let i = 0; i < minhaArray.length; i++) {

  console.log(minhaArray[i]);
}

### Usando o "forEach" para acessar cada item da Array.

minhaArray.forEach(function(minhaArray) {

   console.log(minhaArray);
});
-	## Listar em ordem alfabética -

minhaArray.sort();

for (let i = 0; i < minhaArray.length; i++) {

  console.log(minhaArray[i]);
}

-	## Adicionar (ultimo) -

minhaArray.push('melancia');

console.log(minhaArray);

-	## Adicionar (index) -

### No index (2), removendo (0) itens, adiciona o item ('kiwi').

minhaArray.splice(2, 0, 'kiwi');

console.log(minhaArray);

-	## Remover (ultimo) -

let removeFim = minhaArray.pop();

console.log(minhaArray);

-	## Remover (index) -

### Remove do indice (2) apenas (1) item.

minhaArray.splice(2, 1);

console.log(minhaArray);

-	## Separar - 

-	## Juntar Arrays -  
-	## Converter em String - 
-	## Inverter Ordem - 
-	## Confirmar Elemento - 
