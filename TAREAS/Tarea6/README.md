<div align= "justify">

# TAREA 6: ER Gestión Docente.
  
<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/ER/tareas/tarea12/img/docente.png" width ="600px" heigh="600px"/>
</div>

### Diseñar una Base de Datos para representar la información docente de un colegio, sabiendo que:  

- La formación abarca ocho cursos (1º, 2º, 3º .. 8º) en los que se imparten diversas asignaturas, tales como Matemáticas, Física, Ciencias Naturales, Sociales, Dibujo, etc., dándose el caso de algunas asignaturas de distintos cursos que tienen el mismo nombre. 

- Cada curso se reparte en varios grupos de alumnos a los que se asigna una letra: p.e. 3ºA, 2ºD, 5ºC, 1ºB, y se ubican en un aula fija para todo el curso. 

- Las aulas, identificadas por un número, tienen una determinada capacidad de número de alumnos. De ellas interesa conocer, además, si disponen o no de conexión a la red de computadores del centro, y de pantalla para la proyección de transparencias. 

- Los profesores del centro, de los que se dispone de su nombre y apellidos, DNI, dirección y teléfono, pueden impartir varias asignaturas distintas a grupos distintos. Además, cada curso tiene un profesor coordinador y cada grupo un profesor tutor. 

- Acerca de los alumnos, además de su nombre y apellidos, dirección y teléfono, se desea reflejar el curso en que están matriculados y el grupo al que están asignados. También se desea representar qué alumno es el delegado de cada grupo. Como puede darse el caso, de alumnos con el mismo nombre y apellidos, cada alumno tiene asociado un (único) número de matrícula que facilita su identificación.
  
Se pide:

1. Proponer las frases que describan el problema.
2. Identifica las posibles entidades, relaciones, valores de domino,etc.
3. Monta correctamente todas las entidades y sus relaciones.
4. Colocar los atributos a cada entidad e interrelación.
5. Indica la cardinalidad de las relaciones, y explicar aquellas que se requieran necesarias.

<br>

<details>

  <summary>SOLUCIÓN PASO 1</summary>

- Deseamos conocer en cuantos grupos se dividen los diferentes cursos y el número de asignaturas que son impartidas en ellos. Además, querremos comprobar donde se ubica el aula fija de cada grupo.  
  
- El número de profesores que tiene cada curso y cada grupo y de que tipo son (coordinador o tutor), además de cuantas asignaturas imparten.
  
- Por último, tendremos en cuenta el número de alumnos asignados a cada grupo y cuantos están matriculados en cada curso. Cada grupo de alumnos tendrá asignado un delegado.
  
  
</details>


<details>

  <summary>SOLUCIÓN PASO 2</summary>
  
  <br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea6/IMG/ER.n%C2%BA12.Tarea6.Gesti%C3%B3n%20docente-PASO2.drawio.png">
  
  <br>
  
  
</details>


<details>

  <summary>SOLUCIÓN PASO 3</summary>
  
  <br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea6/IMG/ER.n%C2%BA12.Tarea6.Gesti%C3%B3n%20docente-PASO3.drawio.png">
  
  <br>
  
</details>

<details>

  <summary>SOLUCIÓN PASO 4</summary>
  
   <br>
  
   <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea6/IMG/ER.n%C2%BA12.Tarea6.Gesti%C3%B3n%20docente-PASO4.drawio.png">
  
   <br>
  
</details>

<details>

  <summary>SOLUCIÓN PASO 5</summary>
  
   <br>
  
   <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea6/IMG/ER.n%C2%BA12.Tarea6.Gesti%C3%B3n%20docente-PASO5.drawio.png">
  
   <br>
  
</details>
</div>

