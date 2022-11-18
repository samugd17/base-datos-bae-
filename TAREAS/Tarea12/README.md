<div align="justify">

# Ejercicio Normalización 1: Gestión de Aeropuertos 

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea1/img/aena_logo.png" width="400px"/>
</div>

Se ha creado una base de datos con los datos de ciudades y sus aeropuertos. Los campos y los tipos de datos son los que se indican a continuación:
- Ciudad: Nombre de la ciudad (único).
- HabCiudad_M: número de habitantes de la ciudad en millones. 
- País: País en el que se encuentra la ciudad.
- HabPais_M: Número de habitantes del país en millones.
- PerteneceUE: campo booleano. TRUE si el país Pertenece a la Unión Europea; FALSE, no pertenece a la Unión Europea. 
- codigoAeropuerto: único.
- NombreAeropuerto: único.
- Distancia_km: distancia del aeropuerto a la ciudad en km.

La representación de la información dentro de la BBDD es la siguiente:


<div align="center">
 <img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea1/img/tabla.png" />
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


  1. Claves candidatas:
  - __Ciudad, CodAeropuerto__.
  - __Ciudad, NombreAeropuerto__.
 
 <br/>
  
  2. No cumple la primera forma normal dado que tiene valores multivaluados. Los campos **CodAeropuerto, NombreAeropuerto y distancia_km** no son atómicos.
 
  <br/>
  
  3. La relación es de tipo **N:N** si suponemos que una ciudad puede tener varios aeropuertos y que un aeropuerto puede estar en 
  varias ciudades.

  <div align="center">  
  
_**Ciudad**_
   
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea12/IMG/NMR1.drawio.png"/>
  </div>

<div align="center">
 
  <br/>

_**Ciudad_aeropuerto**_  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea12/IMG/NMR2.drawio.png"/>
</div>

<div align="center">
 
  <br/>

_**Aeropuerto**_  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea12/IMG/NMR3.drawio.png"/>
</div>
 
  <br/>
  
  4. Se crean nuevas tablas reordenando los campos que los componen. Ver imágenes anteriores. 

  5. Indicar claves candidatas de todas las tablas resultantes.
  - **ciudad**: ciudad.
  - **ciudad_aeropuerto**: codAeropuerto y ciudad.
  - **aeropuerto**: codAeropuerto.

</details>

 </div>
