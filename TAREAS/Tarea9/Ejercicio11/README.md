<div align="justify">

# Modelo MR nº11: Empresa Discográfica

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/MR/tareas/tarea11/img/discografica.png" width="400px"/>
</div>

</br>

Una empresa discográfica emergente de Canarias quiere almacenar y organizar eficientemente la información sobre grupos musicales, canciones y músicos. Para ello se hace necesario crear una base de datos que incluya los siguientes requerimientos y consideraciones:
- Un Músico se identifica por un código de músico, su nombre, su fecha de nacimiento, su año de fallecimiento, su género y su nacionalidad.
- Una Banda tiene un identificador de banda, el nombre del grupo, el año de formación, el año de disolución, el estilo musical y el país de origen. El estilo musical sólo puede tomar los valores:Blues, Country, Heavy, Jazz, Pop,Punk, Reggae ,Rock, Soul, Thrash, Techno.
- Un Álbum se caracteriza por incluir un identificador de álbum, su título, el año de publicación, su duración y el identificador del grupo que lo ha grabado.
- Una Canción almacena su identificador de canción, su título, su duración y el identificador del álbum al que pertenece.
- Es necesario también mantener información sobre los músicos que forman parte, es decir, son miembros de un grupo o grupos musicales, así como del instrumento que toca el músico en el grupo, existiendo la posibilidad de que un músico toque más de un instrumento en un grupo.
- Así mismo, también se debe disponer de información sobre las canciones y el músico o músicos que las han compuesto. En este sentido, como es lógico y habitual, un músico puede componer varias canciones y, también, una canción puede estar compuesta por más de un músico.


_**Se solicita**: A partir del modelo entidad-relación, establece el modelo relacional._


<details>
      <summary>MODELO ENTIDAD-RELACIÓN</summary>   
  </br>
  
  <img src="https://github.com/jpexposito/base-datos/raw/main/MR/tareas/tarea11/img/musica-diagrama.drawio.png">
  
  </br>

</details>

<details>
      <summary>MODELO RELACIONAL</summary>   
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea9/Ejercicio11/IMG/MR.N%C2%BA11.drawio.png">
  
  </br>
  
</div>
