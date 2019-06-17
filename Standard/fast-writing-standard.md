Aunque la función ReAb.create() de la librería de ProReLedge https://github.com/opensourceducation/ProReLedge provee un API sencillo para que el desarrollador no tenga que preocuparse por standares, y colocar el contenido requerido de manera sencilla para convertir la información en acordeones digitales, esta podría considerarse una ayuda o guía visual para convertir un texto plano, evernote, o apuntes que ya tengas en ReAbs, sin necesidad de hacer una cantidad de modificaciones grande

Considérese esto una especie de markdown para escribir acordeones (ReAbs)

## Uso1
Una vez tengas tus apuntes en .txt con este standard, escribir en consola el comando `npm run create  ./rutaDelArchivoDeTexto`

## Uso2
Usando la misma función para crear acordeones ReAb.create() y pasarle como argumento un string en lugar de un objeto


Si crees que hay formas de mejorarlo para modificar lo menos posible tus apuntes de estudio, no olvides dejar tus sugerencias




# Escritura basica

Escribe en un mismo renglón o linea las preguntas con sus respuestas, la separación entre preguntas y respuestas puede hacerse con 2 o más espacios, o 2 o más guiones medios espaciados de la respuesta.

1 o más espacios vacíos indican la separación para introducir un acordeón nuevo

Para colocar mas de una pregunta o respuesta posible dentro del acordeón, utiliza la coma para separarlas

Los caracteres especiales se escapan con un & antes del signo

## Ejemplo valido
```
PREGUNTA  RESPUESTA

PREGUNTA, pregunta 2, pregunta 3  RESPUESTA 1, respuesta 2, respuesta 3

el cielo&, es:  Azul

PREGUNTA -- RESPUESTA

PREGUNTA-- RESPUESTA
```
Aquí se estan creando 5 acordeones con sus respectivas preguntas y respuestas

El acordeón 2 contiene 3 formas de preguntar posibles y 2 respuestas válidas

El acordeón 3 es un ejemplo en el que se escapa el caracter coma teniendo una sola pregunta


# escritura alternativa pregunta respuesta
En lugar de separar por dobles espacios o guiones, puedes escribir aquello que sea una respuesta dentro de parentesis 

## Ejemplos válidos
```
   \D (caracteres que no sean dígitos)

   \w (caracteres de palabras) (caracteres de letras)

   \s-- espacios  

   \d , [0-9] (dígitos)   

```
EJEMPLO DE 4 ACORDEONES DE EXPRESIONES REGULARES

Si hay mas de una pregunta, esta se escribe dentro de otro parentesis (ejm: acordeon 2)

En este modo de escritura, no es necesario escapar las comas dentro de las preguntas 

Se puede alternar la escritura de formas de anotar preguntas y respuestas, siempre y cuando se alterne la escritura en acordeones diferentes  (ejm: acordeon 3)





#  (results) (respuestas erroneas)   (recursos externos)    

results   ^r   cuando se busca un resultado sin impoertar la respuesta para llega a el

respuestas erroneas   xx    

como colocar fotos u otros recursos a los acordeones  º  o  ª   (cualquiera de las 2 opciones)

## Ejemplos válidos
```
caracteres que no sean dígitos, xx caracteres que si sean digitos (\D)

4x5 ^r 20

(dog) perro, º./perro.png, ºhttps://www.fotosdeanimales.com/perro
```



# (tags)

Los tags, types o etiquetas se escriben dentro de los siguientes signos <> 
son opcionales
puedes escribir una etiqueta al finalizar cada acordeón o una etiqueta al final para todos los acordeones escritos

En caso de no haber etiquetas, se coloca una etiqueta de tipo básica como <concepts> o <code> según el contenido detectado en los acordeones, por lo que colocarlas es completamente opcional


## Ejemplos con tags al final
```
   \D (caracteres que no sean dígitos)

   \w (caracteres de palabras) (caracteres de letras)

   \s-- espacios  

   \d , [0-9] (dígitos)   

   </code,regexp>
```

```
   \D (caracteres que no sean dígitos)

   \w (caracteres de palabras) (caracteres de letras)

   \s-- espacios  

   \d , [0-9] (dígitos)      
   </code,regexp>
```






## Ejemplo con tags en cada acordeón
```
   \w (caracteres de palabras) (caracteres de letras)
   </code,regexp>

   \s-- espacios
   </code,regexp>  

   \d , [0-9] (dígitos) 
   </code,regexp>  
```

```
   \w (caracteres de palabras) (caracteres de letras)

   \s-- espacios
   </code,regexp>  

   \d , [0-9] (dígitos) 
   </code,regexp>  
```

En este ejemplo, el primer acordeón no tiene etiqueta, por lo que por default se le pondrá una etiqueta al momento de convertirlo en acordeón




# FUNCIONES AVANZADAS

multiprocesos   -->

bifurcaciones entre procesos   --<

expresiones regulares

anotaciones

Respuestas o resultados espaciales

Anexar recursos como material de apoyo