# TITULO



Se necesita un salto de linea mas para hacer un salto de linea convencional. ej

Para hacer ese salto, tuve que bajar dos lineas.

Otro ej con un solo salto de linea:

uno 
dos 
tres

Con dos solo salto de linea:

uno

dos

tres

Negrita e italica:

para poner negrita se usan **doble asterisco** y para italica se encierra con _guiones bajos_ o con un solo asterisco *ejemplo*

Para rayar un contenido se usa ~~doble tilde~~

# Titulo h1
## Titulo h2
### Titulo h3
#### Titulo h4  
etc

-----
Con los "----" se hace un "hr" de html

Para hacer links se puede encerrar en <>  ej: <http://www.google.com>

Para hacer anclas clickeables para links se usa [google](http://www.google.com)

[nombre a aclar] seguido de (link de pagina)

Si se pone un string en los parentesis, se muestra info on hover. ej:

[nombre a aclar](https://google.com "pagina de google")

Se puede reemplazar los links con claves/variables (pueden ser numeros o nombres, como variables):

ej:  podes entrar a una pagina de esta manera: [PAGINA][1] 

[1]: http://www.google.com


# Imagenes
Se comportan como links

"!" para  indicar que es una imagen, [] para el alias y () para el link de la imagen

ej: ![imagen a mostrar](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_1280.jpg "descripcion de la img")

de la misma manera se puede realizar con una "variable"
ej: ![imagen a mostrar][imagen]

[imagen]: https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_1280.jpg

Redirigir a la imagen mas grande:

# HTML y Markdown se pueden usar en el mismo archivo

## inclusive se pueden poner <"style"> tags para influir en el contenido

<style>
   body{
        font-size: px;
   } 
</style>


# Unordered Lists
se pueden hacer con * o +  o - o intercambiarlas:

* asd
* asd
* asd

## Lista Ordenada
con "1. " se comienza una lista ordenada y esta se encarga de aumentarlo automaticamente. Ej:
1. asd
1. asdasd
1. asdasd

Para nestear se indenta:
1. asd
   * indentado
   * asdasdasd
2. asdasd
3. asdasd

## blockquotes
   >"asdasdasdbkjnkjnjnkajnksasdasdd" .
   >
   > *mahatma ghand*i
   >

   

   ## CODE BLOCKS
Se hace con un tab de indentacion o 3 backticks para especificar el lenguaje.

Ej con tab:

    let x = 1;
    console.log(x);

Ej con backticks: (tiene syntax highlighting si el previewer lo dispone)

```javascript
    let x = 1;
    console.log(x);
```
```php
    $age = 1;
    console.log($age);
```

```java
    int a = 0;
    if(true){

    }

```


De la misma manera si se quiere resaltar texto se puede hacer con backticks de esta manera `hola mundo`, o un codigo `console.log("asd")`

### DIFFS
```diff
let x = 100;
- let y = 200;
+ let y = 300;
```

## Checkboxes
* [ ] todo1
* [x] todo2 .............  // marcado
* [ ] todo3


## TABLAS
con los ":" se alinea el texto ":" a la izq o dcha alinean respectivamente y ":" en los dos extremos, lo centran

| Nombre | Edad |
|:----------:|:----------:|
| Juan Manuel | 33 |
| Melisa | 31 
