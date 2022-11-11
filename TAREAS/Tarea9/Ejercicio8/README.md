<div align="justify">

# Modelo MR nº8: Sistema Instituto Secundaria

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/MR/tareas/tarea8/img/alumnos_clase.png" width="400px"/>
</div>

</br>

Queremos recoger la información correspondiente a las aulas de un instituto de secundaria con la especialidad de informática:

- De cada aula se quiere recoger la siguiente información: NºAula, Piso, Pasillo, Nº plazas. El número de aula es único y distinto para todas ellas.
- Cuando las aulas son salas de ordenadores necesitamos saber: nº de ordenadores, escáner y nº de impresoras, así como otros equipamientos que pudieran instalarse.
- Si se trata de laboratorios queremos saber el tipo (de ciencias, de idioma, etc.) y el equipamiento que tiene.
- Todas las aulas, sean comunes, laboratorios o salas de ordenadores, pueden tener o no proyector y pizarra interactiva.
- Existen otros tipos de aulas no recogidos en el modelo anterior como gimnasio, biblioteca, etc.
- Cada aula se utiliza únicamente para las funciones que tiene asignadas (no se imparte una clase normal en un laboratorio, etc.)

- Además, se ha determinado que se debe almacenar la información de las fábricas. Sin embargo, dado el
uso de distribuidores, se usará: Número de la fábrica (único) y Teléfono de contacto. Y se desean ver cuántos artículos (en total) provee la fábrica. También, por información estratégica, se podría incluir información de fábricas alternativas respecto de las que ya fabrican artículos para esta empresa.

__Nota__: Una dirección se entenderá como Nº, Calle, Ciudad y Provincia . Una fecha incluye hora.

_**Se solicita**: A partir del modelo entidad-relación, establece el modelo relacional._

<details>
<summary>MODELO ENTIDAD-RELACIÓN</summary>

  </br>
  
  <img src="https://github.com/jpexposito/base-datos/raw/main/MR/tareas/tarea8/img/aula-paso-2.drawio.png">
  
  </br>
</details>

<details>
<summary>MODELO RELACIONAL</summary>
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea9/Ejercicio8/IMG/MR.N%C2%BA8.drawio.png">
  
  </br>
</details>


</div>
