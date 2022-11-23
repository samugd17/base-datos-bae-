<div align="justify">

# Ejercicio de NormalizaciGestión de INEM

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea3/img/inem.png" width="400px"/>
</div>
<br>

Tenemos una empresa publica donde los puestos de trabajo, están regulados por el estado, de modo que las condiciones salariales están determinadas por el puesto de trabajo, se ha creado el siguiente esquema relacional:
(con el ___número de la seguridad social NSS como clave primaria__)
La representación de la información dentro de la BBDD es la siguiente:

<div align="center">

__Empleados (NSS, Nombre, puesto, salario, emails)__

 <img src="https://github.com/jpexposito/base-datos/raw/main/NORMALIZACION/tareas/tarea3/img/tabla.png" width="400px"/>
 </div>

Se pide:
1. Indicar claves candidatas.
2. Comprobar si se cumple la 1ª Forma Normal.
3. Normalizar si no se cumple el apartado 2.
4. Comprobar si se cumple la 2ª Forma Normal.
5. Normalizar si no se cumple el apartado 4.
6. Comprobar si se cumple la 3ª Forma Normal.
7. Normalizar si no se cumple el apartado 5.
8. Indicar claves candidatas de todas las tablas resultantes.
9. Genera el __diagrama E/R resultante__.
 
 ### _**Resolución paso 1:**_
 - NSS.
- Emails.
 ### _**Resolución paso 2:**_
 La primera forma normal no se cumple, ya que los valores del campo emails no son atómicos.
 
 ### _**Resolución paso 3:**_
 
 <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea14/IMG/1FN.drawio.png">
 
 ### _**Resolución paso 4:**_
 
 No se cumple la 2FN, ya que el atributo puesto y salario no depende funcionalmente de NSS, que en este caso es nuestra clave principal.
 
 NSS $\rightarrow$ Nombre, puesto, email.
 
 Puesto $\rightarrow$ Salario.
 
 ### _**Resolución paso 5:**_
 
 <div align="center">
  
 _**Empleado-Trabajo**_
  
   <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea14/IMG/ERMR-Empleado-Trabajo.drawio.png">
 
 <br>
 <br>
  <br>
 <br>
 
 _**Empleado-Email**_
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea14/IMG/ERMR-Empleado-Email.drawio.png">
  
 </div>
 
 ### _**Resolución paso 6:**_
 ### _**Resolución paso 7:**_
 ### _**Resolución paso 8:**_
 ### _**Resolución paso 9:**_

</div>
