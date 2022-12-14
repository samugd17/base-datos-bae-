<div align="justify">

# Ejercicio Normalización 2: Gestión Escuela de Topografía de Madrid

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea2/img/topografia.png" width="400px"/>
</div>

Se ha creado una base de datos para llevar las calificaciones de las asignaturas de los alumnos de primer curso de la Escuela de Topografía de Madrid.
La tabla creada tiene los siguientes campos
- DNI varchar (20).
- Apellidos varchar (255).
- Nombre varchar (50).
- Dirección varchar (255).
- Ciudad varchar (50).
- Provincia varchar (50).
- Comunidad varchar (50).
- Código integer.
- Asignatura varchar(50).
- Nota double.

Además la información que se aporta es:
- DNI es un identificador único del alumno; lo mismo que {Apellidos, Nombre}.
- Ciudad es el nombre de la ciudad de residencia (único)
- Provincia es el nombre de la provincia de residencia (único)
- Com_Aut es el nombre de la Comunidad Autónoma de residencia (único)
- Codigo es el código de una asignatura (único). Asignatura es el nombre de la asignatura (único)
- Asignatura es el nombre de la asignatura (único)
- Nota es la nota que el alumno ha obtenido en la asignatura
- Código, Asignatura y Nota se escriben en el mismo orden en los campos correspondientes

Ejemplo de datos de la tabla:

<div align="center">
 <img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea2/img/tabla.png" />
 </div>

Se pide:
1. Indicar claves candidatas.
2. Comprobar si se cumple la 1ª Forma Normal.
3. Normalizar si no se cumple el apartado 2.
4. Determinantes sobre las tablas resultado del apartado 3.
5. Indicar claves candidatas de todas las tablas resultantes.

  <details>
      <summary>SOLUCIÓN</summary>
  </br>

  _**RESOLUCIÓN PASO 1:**_
  
  - DNI, Asignatura. 
  - Apellidos, Nombre, Asignatura.
  - DNI, Código.
  - Apellidos, Nombre, Código.
  
  _**RESOLUCIÓN PASO 2:**_

No cumple la primera forma normal porque los campos **Código, Asignatura y Nota** no son atómicos.
    
  _**RESOLUCIÓN PASO 3:**_


<div align="center">

_**Alumno**_

 <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea13/IMG/NMR1%20Alumno.drawio.png" />
 </div>

 <div align="center">
 
 <br>

_**Asignatura**_

 <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea13/IMG/NMR2%20Asignatura.drawio.png"/>
 </div>
 
 <br>

 <div align="center">

 _**Alumno-Asignatura**_

 <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea13/IMG/EjercNMR3%20Alumno_Asignatura.drawio.png"/>
 </div>
 
 <br>

  _**RESOLUCIÓN PASO 4:**_
  
  Se relacionan los campos según se indica en la imagén anterior.
  
  _**RESOLUCIÓN PASO 5:**_
  
  - Alumno: DNI.
  - Asignatura: Código.
  - Alumno-Asignatura: DNI,Código.


 </details>

 </div>
