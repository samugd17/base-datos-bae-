<div align="justify">

# Gestión de Aeropuertos 

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


  1. Las claves candidatas son:
  - __Ciudad, CodAeropuerto__.
  - __Ciudad, NombreAeropuerto__.
  
  2. No cumple la 1 forma normal dado que tiene __valores multivaluados__. Los campos __CodAeropuerto, NombreAeropuerto y distancia_km__ no son atómicos.
  
  3. - La relación es de tipo **N:N** si suponemos que una ciudad puede tener varios aeropuertos y que un aeropuerto puede estar en 
  varias ciudades.

  <div align="center">  
  
  _**ciudad**_

  <img src="" width="400px"/>
  </div>

<div align="center">

_**ciudad_aeropuerto**_  
  <img src="" width="300px"/>
</div>

<div align="center">

_**aeropuerto**_  
  <img src="" width="250px"/>
</div>
  
  4. Determinantes sobre las tablas resultado del apartado 3. 
  Se crean nuevas tablas reordenando los campos que los componen. Ver imágenes anteriores. 

  5.Indicar claves candidatas de todas las tablas resultantes.
  - **ciudad**: ciudad.
  - **aeropuerto**: codAeropuerto.
  - **ciudad_aeropuerto**: codAeropuerto y ciudad.

</details>

 </div>
