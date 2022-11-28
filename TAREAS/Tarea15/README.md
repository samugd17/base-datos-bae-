<div align="justify">

# Ejercicio Normalización 4: Editorial

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea4/img/biblioteca.png" width="400px"/>
</div>

Tenemos una __biblioteca__ que tiene como objetivo la gestión de la información de sus libros y lectores.

La representación de la información dentro de la BBDD es la siguiente:


| CodLibro | Titulo| Autor |Editorial | NombreLector| FechaDev | 
|-----|-----|-----|-----|-----|-----| 
| 1001 | Variable compleja  |  Murray Spiegel  | McGraw Hill |Pérez Gómez, Juan |15/04/2022 |
 |1004 | Visual Basic 5 | E. Petroustsos | Anaya | Ríos Terán, Ana | 17/04/2022  | 
 | 1005 | Estadística | Murray Spiegel | McGraw Hill | Roca, René | 16/04/2022  | 
 | 1006  | Oracle University | Nancy Greenberg y Priya Nathan | Oracle Corp. | García Roque, Luis | 20/04/2022 | 
| 1007 | Clipper 5.01 | Ramalho | McGraw Hill | Pérez Gómez, Juan | 18/04/2022 |

Se pide:

_**1. Comprobar si se cumple la 1ª Forma Normal.**_

La primera forma normal no se cumple ya que dentro del apartado autor hay atributos multivaluados.

_**2. Normalizar si no se cumple el apartado 2.**_

<img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea15/IMG/NMR1.drawio.png"/>

_**3. Comprobar si se cumple la 2ª Forma Normal.**_
 
 No se cumple la 2FN, ya que los atributos NombreLector y FechaDev no depende funcionalmente de CodLibro, que en este caso es nuestra clave principal.
 
 CodLibro $\rightarrow$ Título, Autor, Editorial
 
 NombreLector $\rightarrow$ FechaDev
 
_**4. Normalizar si no se cumple el apartado 4.**_
 
 <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea15/IMG/NMR2(Libro-leer-lector).drawio.png"/>
 
 <br>
 <br>
 <br>
 
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea15/IMG/NMR2(Libro-tiene-autor).drawio.png"/>
 
 
 
_**5. Comprobar si se cumple la 3ª Forma Normal.**_
 
_**6. Normalizar si no se cumple el apartado 5.**_
 
_**7. Indicar claves de todas las tablas resultantes.**_
 
_**9. Genera el __diagrama E/R resultante__.**_
