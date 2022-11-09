<div align="justify">

# Ejercicio Básico Nº3: Sistema de Artículos - Encargos

<div align="center">
<img src="https://github.com/jpexposito/base-datos/raw/main/ER/tareas/tarea3/img/articulos-proveedores.png" width="400px"/>
</div>


Se desea crear una base de datos para una pequeña empresa debe contener información acerca de clientes, artículos y
pedidos.
Hasta el momento se registran los siguientes datos en documentos varios:
 - Para cada cliente: Número de cliente (único), Direcciones de envío (varias por cliente), Saldo, Límite de crédito (depende del cliente, pero en ningún caso debe superar los 3.000.000 €), Descuento.
 - Para cada artículo: Número de artículo (único), Fábricas que lo distribuyen, Existencias de ese artículo en cada fábrica, Descripción del artículo.
- Para cada pedido: Cada pedido tiene una cabecera y el cuerpo del pedido. La cabecera está formada por el número de cliente, dirección de envío y fecha del pedido. El cuerpo del pedido son varias líneas, en
cada línea se especifican el número del artículo pedido y la cantidad.

- Además, se ha determinado que se debe almacenar la información de las fábricas. Sin embargo, dado el
uso de distribuidores, se usará: Número de la fábrica (único) y Teléfono de contacto. Y se desean ver cuántos artículos (en total) provee la fábrica. También, por información estratégica, se podría incluir información de fábricas alternativas respecto de las que ya fabrican artículos para esta empresa.

__Nota__: Una dirección se entenderá como Nº, Calle, Ciudad y Provincia . Una fecha incluye hora.

  </br>
  
  <img src="https://github.com/jpexposito/base-datos/raw/main/MR/tareas/tarea3/img/articulos-encargo-solucion-2.drawio.png">
  
  </br>

<details>
    <summary>Modelo MR</summary>
  </br>
  
  <img src="">
  
  </br>
</details>

</div>
