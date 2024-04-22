# STRING
es un tipo de objeto que representa una secuencia de caracteres, es decir, texto. Este objeto proporciona una serie de métodos y propiedades que permiten manipular y trabajar con cadenas de caracteres de manera eficiente.

- 1° Declaración de una cadena de caracteres:
Puedes crear un objeto String utilizando comillas simples ('') o comillas dobles ("").

```Javascript
let nombre = "Juan";
let apellido = 'Pérez';
```

- 2° Acceso a propiedades y métodos:
Puedes acceder a propiedades y métodos de los objetos String para realizar operaciones como obtener la longitud de la cadena o convertirla a mayúsculas.

```Javascript
let mensaje = "Hola mundo";

// Propiedad length: obtiene la longitud de la cadena
console.log(mensaje.length); // Salida: 10

// Método toUpperCase(): convierte la cadena a mayúsculas
console.log(mensaje.toUpperCase()); // Salida: HOLA MUNDO
```

- 3° Concatenación de cadenas:
Puedes concatenar dos o más cadenas utilizando el operador +.

```Javascript
let saludo = "Hola";
let nombre = "Juan";
let mensaje = saludo + " " + nombre;
console.log(mensaje); // Salida: Hola Juan
```

- 4° Búsqueda de subcadenas:
Puedes buscar subcadenas dentro de una cadena utilizando el método indexOf().

```Javascript
let frase = "La casa es grande";
console.log(frase.indexOf("casa")); // Salida: 3
```

- 5° Extracción de subcadenas:
Puedes extraer partes de una cadena utilizando el método substring().

```Javascript
let frase = "La casa es grande";
console.log(frase.substring(3, 7)); // Salida: casa
```

Estos son solo algunos ejemplos de cómo puedes trabajar con objetos String en JavaScript. Los objetos String son muy versátiles y ofrecen una amplia gama de funcionalidades para manipular texto en tus aplicaciones.