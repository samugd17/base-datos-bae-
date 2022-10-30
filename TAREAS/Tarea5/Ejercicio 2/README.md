<div align="justify">

# Ejercicio ER nº2: Sistema de ventas

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/ER/tareas/tarea2/img/sistema-ventas.png" width="400px"/>
</div>


Se desea realizar una BD que permita apoyar la gestión de un sistema de ventas. La empresa necesita llevar un control de proveedores, clientes, productos y ventas.

- Un proveedor tiene un identificador, nombre, dirección, teléfono y página web.
- Un cliente también tiene identificador, nombre, dirección, pero puede tener varios teléfonos de contacto. La dirección se entiende por calle, número, provincia y ciudad.
- Un producto tiene un identificador único, nombre, precio actual, stock y nombre del proveedor. Además se organizan en categorías, y cada producto va sólo en una categoría. Una categoría tiene id, nombre y descripción.
- Por razones de contabilidad, se debe registrar la información de cada venta con un id, fecha, cliente, descuento y monto final.
- Además se debe guardar el precio al momento de la venta, la cantidad vendida y el monto total por el producto.

Se pide: 

1. Identifica las posibles entidades y las relaciones.
2. Proponer las frases que describan el problema.
3. Generar y montar los entidades y relaciones de cada frase que hayas detectado, sin indicar cardinalidad, etc.
4. Colocar los atributos a cada entidad e interrelación.
5. Indica la cardinalidad de las relaciones.

- - -

<details>
      <summary>RESOLUCIÓN PASO 1:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%202/IMG/ER.n%C2%BA2.PASO1.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 2:</summary>
 
- Deseamos conocer el número de productos que un proveedor puede suministrar.
- Saber las diferentes categorías en las que se puede clasificar un producto.
- Conocer los detalles de la venta de cada producto.
- Cuantificar cuantas compra puede hacer un cliente.
        
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 3:</summary>
      
  <br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%202/IMG/ER.n%C2%BA2.PASO3.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 4:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%202/IMG/ER.n%C2%BA2.PASO4.drawio.png">
  
  </br>
  
</details>

<details>
      <summary>RESOLUCIÓN PASO 5:</summary>
      
  </br>
  
  <img src="https://github.com/samugd17/base-datos-bae-/blob/main/TAREAS/Tarea5/Ejercicio%202/IMG/ER.n%C2%BA2.PASO5.drawio.png">
  
  </br>
  
</details>
</div>

