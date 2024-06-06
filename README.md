# Type Conversion (conversão de tipo) / Type Coercion (Coerção de tipo)

```js
   var x = Number ("0") //type conversion, nessa linha é feita uma conversão de tipo explicita
   var y = "2" + 3 // type coercion, nessa linha é feita uma conversão  implicita do valor 3 que é numérico(number) para texto(string)

   //onde usa expressões condicional e repetição, faz necessário um valor boolean (verdadeiro ou falso)
   //Ex:
     if(true) {
   }

   //Caso não for informado uma expressão ou um valor boolean diretamente, ele fará um Type Coercion (coerção de tipo)
   //Ex:
     if (0){ //Nessa linha ele ira fazer uma conversão do 0 para um boolean (true ou false), nesse caso 0 será falso.}


```
