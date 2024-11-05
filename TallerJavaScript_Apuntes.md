<!-- Lenguaje Markdown:
Objetivo: Proporcionar una herramienta para documentar código o aspectos técnicos para compartirlos o tenerlos de referencia en mi GIT u otra plataforma. -->

<!-- Markdown es un lenguaje de marcado ligero creado en 2004 por John Gruber.
Trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

El objetivo de su creador fue que la gente pudiera escribir usando un formato de texto plano fácil de leer, fácil de escribir y con la posibilidad de convertir su documento en HTML válido.

La gran simpleza de su sintaxis hizo que tuviera una rápida adopción y popularidad en la comunidad de desarrolladores. Actualmente permite generar contenido HTML de forma dinámica. -->

## Conocer Sintaxis Markdown

### 1. Párrafos
"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo."

_Cursiva_  
**Negrita**  
~~Tachado~~  
**_Cursiva y Negrita_**  
_~Cursiva y Tachado~_  
**~Negrita y Tachado~**  
**_~Cursiva, Negrita y Tachado~_**

### Encabezados
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6

### Divisiones
Un bloque de contenido  
---  
Este es otro bloque de contenido

### Listas
Podemos utilizar listas ordenadas y desordenadas.

1. HTML5
2. CSS
3. JavaScript
4. Ajax
5. JSON

- HTML5
- CSS
- JavaScript
- Ajax
- JSON

### Citas
Podemos dar formato de cita a un texto anteponiendo a la línea de texto un carácter de mayor que (>).

> La IA en el futuro remplazará a muchas profesiones de TI. - Adrián  
> ChatGPT debe potenciar mi aprendizaje, no suprimir mi estado autodidacta.  
> - Adrián

### Enlaces
[YouTube](https://www.youtube.com)  
[Enlace a Google](https://www.google.com)

### Imágenes
![Texto alternativo](URLdelaImagen)

### Tablas
| Columna 1 | Columna 2 | Columna 3 |
| --------- | --------- | --------- |
| A         | B         | C         |
| D         | E         | F         |
| G         | H         | I         |

### Código
Podemos dar formato a un texto en línea usando el acento grave (\`).

Esto es un `código` en línea.

En JavaScript, una variable se define así:
`let saludo = "Hola Mundo";`

Para un bloque de código completo utilizamos tres acentos graves seguidos de `js`:

```js
let estudiante = "Adrián Mtz";
let edad = "30";
let isEstudiante = true;
let calificacion = 90.2;

// Operadores aritméticos
let a = 10;
let b = 5;
console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
console.log(a % b);

// Operadores de asignación
let x = 10;
x += 5;
x -= 2;
x *= 3;
x /= 3;
x %= 5;

// Operadores de comparación
let aa = 5; 
let bb = '5';
console.log(a == b);
console.log(a === b);
console.log(a != b);
console.log(a !== b);
console.log(a > 3);

// Operadores lógicos
let d = true;
let t = false;

// alert("Estamos en el archivo de estructuraciclo.js")

for(let i=0;i<=10;i++){
    console.log("[for]No iteracion: "+i);
}
  let contador=1;

  while (contador<10){

    console.log("[while]No iteracion: "+contador);
    contador++;
}
//do / while
let numero=1;
do{
    console.log("[do/while ]No iteracion"+numero);
    numero++;
}while(numero<10);

//for in

let estudiante={nombre:"Adrian", edad:10, calificacion :100};
for(let propiedad in estudiante){
    console.log(propiedad+ ": " +estudiante[propiedad]);
}

//for.. of
//Este ciclo itera sobre los valores de un objeto iterable (como un array).
let mis_numero=[10,20,30,40,50];
for(let numero of mis_numero){
    console.log(numero);
}

