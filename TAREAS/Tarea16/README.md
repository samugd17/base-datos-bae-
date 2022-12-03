<div align="justify">

# Pedidos

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea5/img/pedidos.png" width="400px"/>
</div>

Tenemos una empresa de __pedidos__ que tiene como objetivo la gestión de la información de sus compras.

La representación de la información dentro de la BBDD es la siguiente:

__orden (id_orden, fecha, id_cliente, nom_cliente, ciudad, num_art,
nom_art, cant, precio)__

__(Tabla) Orden__

| Id_orden |  Fecha |  Id_cliente |  Nom_cliente |  Ciudad |  Num_art |  nom_art |  cant |  Precio |
|-----|-----|-----|-----|-----|-----|-----|-----|-----| 
| 2301 |  23/11/22 |  101 |  Martin |  S/C Tenerife |  3786 |  Red |  3 |  35,00 |
| 2301 |  23/11/22 |  101 |  Martin |  S/C Tenerife |  4011 |  Raqueta |  6 |  65,00 |
| 2301 |  23/11/22 |  101 |  Martin |  S/C Tenerife |  9132 |  Paq-3 |  8 |  4,75 |
| 2302 |  25/11/22 |  107 |  Herman |  Las Palmas de Gran Canaria |  5794 |  Paq-6 |  4 |  5,00 |
| 2303 |  27/11/22 |  110 |  Pedro |  San Cristobal de la Laguna |  4011 |  Raqueta |  2 |  65,00 |
| 2303 |  27/11/22 |  110 |  Pedro |  San Cristobal de la Laguna |  3141 |  Funda |  2 |  10,00 |

Se pide:

_**1. Comprobar si se cumple la 1ª Forma Normal.**_
  
La primera forma normal no se cumple ya que la clave principal está repetida.
  
_**2. Normalizar si no se cumple el apartado 2.**_
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea16/IMG/1FN.drawio.png">
  
_**3. Comprobar si se cumple la 2ª Forma Normal.**_

Una Relación está en 2FN si y sólo si está en 1FN y todos los atributos que NO forman parte de la Clave Principal tienen dependencia funcional completa de ella.
 
En este caso, al pasar a primera forma normal extrayendo el atributo de cantidad y convirtiéndolo en una nueva tabla, si que se cumple este apartado tal y como mostramos a continuación.
  
_**4. Normalizar si no se cumple el apartado 4.**_
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea16/IMG/2.FN.drawio.png"> 
  <br>
  <br>
  
_**5. Comprobar si se cumple la 3ª Forma Normal.**_

Una Relación está en 3FN sólo si está en 2FN y no existen dependencias transitivas. Todas las dependencias funcionales deben ser respecto a la clave principal. Por tanto, la 3FN se cumple en este caso, ya que existe no existe transitividad en ningún caso.
  
 _Id_Orden_ $\rightarrow$ _fecha_

_Id_cliente_ $\rightarrow$ _nom_cliente_ $\rightarrow$ _ciudad_.

_Num_art_ $\rightarrow$ _nom_art_ $\rightarrow$ _precio._
  
_Pedido-Compuesto-Artículo_ $\rightarrow$ _Id_Orden_, _Num_art_, _cant_.
 
  
_**6. Normalizar si no se cumple el apartado 5.**_
  
  
_**7. Indicar claves de todas las tablas resultantes.**_
  
**Pedido:** Id_Orden.

**Cliente:** Id_cliente.

**Artículo:** Num_art.
  
**Pedido-Compuesto-Artículo:** Id_Orden, Num_art.
  
  
_**9. Genera el diagrama E/R resultante**_.
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea16/IMG/ER.drawio.png">
