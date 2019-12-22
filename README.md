# Variables

> ¿Que son las variables? Las variables son elmentos que se emplean para almacenar datos.
> 'let' es una variable pero puede cambiar segun el curso del codigo.
```js
// Tipos de variables

let nombre = 'Mario' //  String (texto)

let edad = 17 //  Número

let comidas = ['platano', 'manzana'] // Array

let activo = true //  Booleano (Verdadero o falso)

let familia = {
papa: 'manuel',
mama: 'josefa'.
hijos: ['bartolo', 'nacho']
} //  Objeto
```
#### Ejemplo:
```js
let nombre = 'Mario'
let edad = 17

console.log(nombre, edad = 16)
```
##### Salida
```js
> "Mario" 16
```
 
# Constantes

> ¿Que son las constantes? Las constantes son elementos que sirven para almacenar datos.
> 'const' es una constante que no puede cambiar a lo largo del codigo.

#### Ejemplo
```js
const birthYear = 2002

console.log(birthYear = 2020)

```

##### Salida
```js
// ERROR: La constante birthYear ya esta definida.

> 2002
```

# Funciones

> ¿Que es una funcion? Una funcion es una 'receta' que requiere ingredientes cuales se almacenan.
> Tus ingredientes de la receta son tus datos de la funcion.

#### Ejemplo:
```js

let nombre = 'Mario'

const diHola = function(name) {
return 'Hola' + name
}

diHola(nombre)

```

##### Salida

```js
> "Hola Mario"
```


# Condicionales

> ¿Que es una condicional? Una condicional es un 'Si mi casa es roja haz esto, si no lo es haz lo otro'

#### Ejemplo

```js
let user = {
name: 'Mario',
edad: 17,
padre: false
}

if(user.padre) { /* Si padre es verdad (true) ejecuta la funcion1() */
funcion1()
} else {  /*  Pero si padre no es verdad (false) ejecuta la funcion_no_es_padre() */
funcion_no_es_padre()
}
```

# Ciclos

#### Ejemplo

```js
let amigos = ['Mario', 'Kiera', 'Julio', 'Tom']

for(let i = 0 ; i < amigos.length ; i++) {
  console.log('Hola, ' + amigos[i]) // Le hemos dicho que imprima (escriba) los amigos uno detras de otro
  }
```
##### Salida

```js

> "Hola, Mario"
> "Hola, Kiera"
> "Hola, Julio"
> "Hola, Tom"

```
## Guia realizada por Mario
> Nombre de Discord: [YoSoyMario#0319](https://DiscordApp.com/users/433039910077988874)

> [Servidor de Soporte](https://Discord.GG/yEe8PpZ)

> Si desea tener un soporte mas especifico, o incluso si desea incluir algo o proporcionar una idea contacteme.
