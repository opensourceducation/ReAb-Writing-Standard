ReAb (Relational Abstraction o Acordeones Digitales), es una estructura de datos que propone un standard opensource de escritura de quizzes, y medición de progresos del aprendizaje humano más preciso, como una alternativa futura al sistema de calificaciones, certificaciones, e implementacion de planes de estudio actuales



Creemos que los problemas más graves de la educación,como la latencia de informacion entre los agentes laboral-científico-educativos, y la imposibilidad económica de una educación de alta calidad personalizada, y eficiente para el sistema laboral, pueden resolverse cambiando la forma en la que implementamos el contenido , medimos, evaluamos y certificamos las capacidades académicas de la mayor cantidad de personas posible, que cuenten con un dispositivo electrónico. 




Los acordeones digitales, y la forma de medir y certificar los progresos, son agnósticos de la experiencia de aprendizaje impartida por el educador o software educativo. Pero tiene el potencial de favorecer la inclusión de metodologías de aprendizaje más innovadoras, abiertas, o poco ortodoxas como Montessori, basadas en la experiencia práctica, con o sin un plan de estudio de por medio.




## ARQUITECTURA

Un ReAb guarda relaciones abstractas lo más pequeñas posibles entre palabras, imágenes, texto, y contenido audiovisual. Estas relaciones pueden ser positivas y/o negativas, y poseen una estructura conceptualmente parecida a los acordeones que usabas para estudiar o copiar en los exámenes, solo que a un nivel abstraccional más pequeño. 

Dichas relaciones a su vez, son almacenadas dentro de procesos, y bifurcaciones de procesos necesarias para completar una tarea. Basadas tanto en respuestas prediseñadas, como en un resultado, o rangos de resultados usando expresiones regulares.


Buscando estandares de escritura sencillos, el ReAb debe almacenar desde una relacion sencilla de palabra que se relaciona con otra palabra o imagen, teniendo la etiqueta de cierto idioma o dialecto, hasta tareas que involucran gran complejidad, como  la forma de reaccionar de una consola cuando le introduces ciertos comandos, operaciones matemáticas complejas con distintas resoluciones o procesos para llegar al mismo resultado, o completar una tarea larga en una interfaz gráfica que implica guardar imágenes e instrucciones espaciales, pulsando ventanas y botones para llegar a un menú y teclearle ciertas palabras antes de darle aceptar.


Todo el objeto, desde los procesos, hasta las respuestas anidadas en cada uno de los procesos, contienen una primera unidad de medida sugerida para medir progresos diferente al interruptor binario de si una respuesta es correcta e incorrecta de toda la vida.

Un score de interiorización que mide cualquier reacción de interacción del usuario con el ejercicio expuesto en la aplicación movil, videojuego, plataforma web, o pantalla de desbloqueo del celular.


Dicho score consta de un número que no posee un límite máximo o mínimo ni positiva ni negativamente. Solo es un número incremental o decremental que proporciona información sobre que tan sólida se encuentra la tarea completa, y/o dicho proceso o elección de respuesta específica en el acordeón del usuario, y que solo puede contextualizarse comparando los scores con el análisis de datos de otros usuarios con el mismo ReAb, o con acordeones personalizados que posean las mismas relaciones y etiquetas.


Los elementos actuales para calcular el incremento o decremento del mismo, son la frecuencia de uso y desuso, y la cantidad de tiempo que un usuario puede pasar sin resolver dicho proceso del ReAb de manera exitosa



## Si deseas implementar el uso de ReAbs en tu aplicación educativa, o buscas una herramienta de aprendizaje autodidacta, puedes usar la librería ProReLedge https://www.github.com/opensourceducation/ProReLedge



# No olvides dejar tus sugerencias o modificaciones a la estructura del ReAb en Issues, Pull Request, o Forks del proyecto
