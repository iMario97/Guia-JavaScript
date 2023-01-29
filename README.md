# Variables

> ¿Que son las variables? Las variables son elmentos que se emplean para almacenar datos.
> 'let' es una variable pero puede cambiar segun el curso del codigo.
```js
// Tipos de variables

let nombre = 'manuela'//String (texto)

let edad = 17//Número

let comidas = ['fideos', 'frijoles']// Array

let pendejo = true//(Verdadero o falso)

let familia = {
papa: 'manco',
mama: 'tierrin'.
hijos: ['paulo', 'julio']
}//  Objeto
```
#### Ejemplo:
```js
let nombre = 'Andre'
let edad = 13

console.log(nombre, edad = 18)
//El resultado es Andre 18
```
# Constantes

> ¿Que son las constantes? Las constantes son elementos que sirven para almacenar datos.
> 'const' es una constante que no puede cambiar a lo largo del código.

#### Ejemplo
```js
const link = `https://github.com/iMario97`

console.log(link)
```

##### Resultado
```js
https://github.com/SoyMario97
```

# Funciones

> ¿Qué es una función? Una función es una 'receta' que requiere ingredientes cuales se almacenan.
> Tus ingredientes de la receta son tus datos de la función.

#### Ejemplo:
```js
let nombre = 'Mario'

const diHola = function(name) {
return 'Hola ' + name
}

console.log(diHola(nombre))
//El resultado es Hola Mario
```
#### Ejemplo

```js
let user = {
name: 'Pedro',
edad: 24,
pendejo: false
}

if(user.pendejo) { /* Si pendejo es verdad (true) ejecuta la funcion1() */
funcion1()
} else {  /* si pendejo no es verdad (false) ejecuta la funcion_no_es_pendejo() */
funcion_no_es_pendejo()
}
```

# Ciclos

#### Ejemplo

```js
let amigos = ['Mario', 'Crater', 'Fabricio', 'ManU']

for(let i = 0 ; i < amigos.length ; i++) {
console.log('Wenas, ' + amigos[i])//le hemos dicho que en la consola salga Wenas, <Nombre>
}
```
##### Salida

```js
> "Wenas, Mario"
> "Wenas, Crater"
> "Wenas, Fabricio"
> "Wenas, ManU"
```
## Guia realizada por Mario
> Nombre de Discord: [YoSoyMario#0319](https://DiscordApp.com/users/433039910077988874)

> [Servidor de Soporte](https://Discord.GG/yEe8PpZ)

> Si desea tener un soporte mas especifico, o incluso si desea incluir algo o proporcionar una idea contacteme.
