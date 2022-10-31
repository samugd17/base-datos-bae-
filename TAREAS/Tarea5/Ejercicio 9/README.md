<div align="justify">

# Ejercicio ER Nº9: Campeonato del mundo de Ajedrez

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/ER/tareas/tarea9/img/gambito.png" width="400px"/>
</div>
</br>

El club de Ajedrez IES Puerto, ha sido encargado por la Federación Internacional de Ajedrez de la organización de los próximos campeonatos mundiales que se celebrarán en la mencionada localidad. Por este motivo, desea llevar a una base de datos toda la gestión relativa a participantes, alojamientos y partidas. Teniendo en cuenta qué:
- En el campeonato participan únicamente jugadores y árbitros; de ambos se requiere conocer el número de asociado, nombre, dirección, teléfono de contacto y campeonatos en los que han participado. De los jugadores se precisa además el nivel de juego en una escala de 1 a 10.
- Ningún árbitro puede participar como jugador.
- Los países envían al campeonato un conjunto de jugadores y árbitros, aunque   no todos los países envían participantes. Todo jugador y árbitro es enviado por un único país. Un país puede ser representado por otro país.
- Cada país se identifica por un número e interesa además conocer su nombre y el número de clubes de ajedrez existentes en el mismo.
- Cada partida se identifica por un código ( Cod_P ), jugada por dos jugadores y arbitrada por un árbitro. Interesa registrar las partidas que juega cada jugador y el color ( blancas o negras ) con el que juega. Ha de tenerse en cuenta que un árbitro no puede arbitrar a jugadores enviados por el mismo país que le ha enviado a él.
- Todo participante participa en al menos una partida.
- Tanto jugadores como árbitros se alojan en uno de los hoteles en los que se desarrollan las partidas, se desea conocer en qué hotel y en qué fechas se ha alojado cada uno de los participantes. Los participantes pueden no permanecer en el Puerto durante todo el campeonato, sino acudir cuando tienen que jugar alguna partida alojándose en el mismo o distinto hotel. De cada hotel, se desea conocer el nombre, la dirección y el número de teléfono.
- El campeonato se desarrolla a lo largo de una serie de jornadas (año, mes, día) y cada partida tiene lugar en una de las jornadas aunque no tengan lugar partidas todas las jornadas.
- Cada partida se celebra en una de las salas de las que pueden disponer los hoteles, se desea conocer el número de entradas vendidas en la sala para cada partida. De cada sala, se desea conocer la capacidad y medios de que dispone (radio, televisión, vídeo...) para facilitar la retransmisión de los encuentros. Una sala puede disponer de varios medios distintos.
- De cada partida se pretende registrar todos los movimientos que la componen, la identificación de movimiento se establece en base a un número de orden dentro de cada partida: para cada movimiento se guardan la jugaday un breve comentario realizado por un experto.

Se pide:
1. Identifica las posibles __entidades y las relaciones__.
2. Proponer las frases que describan el problema.
3. Genera y monta las entidades y relaciones de cada frase que hayas detectado, sin indicar cardinalidad, etc.
4. Colocar los atributos a cada entidad e interrelación.
5. Indica la cardinalidad de las relaciones.

- - -

<details>
      <summary>RESOLUCIÓN PASO 1:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%209/IMG/ER.n%C2%BA9.PASO1.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 2:</summary>
 
- Deseamos conocer el número de participantes (Jugadores y árbitros), que juegan o arbitran cada partida respectivamente.

- Estos participantes son enviados por un país que a su vez puede estar representado por otro país.
      
- Además se quiere saber en qué hoteles se alojan los participantes y si estos sitios disponen de salas para llevar a cano las partidas.
      
- De cada partida, se desea registrar el número de movimientos que se dan en ella, el número de jornada que le corresponde y en qué sala se celebra.
        
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 3:</summary>
      
  <br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%209/IMG/ER.n%C2%BA9.PASO3.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 4:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%209/IMG/ER.n%C2%BA9.PASO4.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 5:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%209/IMG/ER.n%C2%BA9.PASO5.drawio.png">
  
  </br>
  
</details>
</div>
