# AluraStore_Challenge
*A Based Learning Challenge from ONE (Oracle Next Education) and Alura Latam*

## Programa Utilizado
Python en el ambiente de un Jypiter Notebook

## Objetivos ##
**Poner en pratica conceptos como:**
* Estructuras de repeticion como **for**
* Listas
* Manipulacion de listas
* Diccionarios
* Listas en diccionarios
* Funciones built-in (incorporadas)
* Bibliotecas
* Biblioteca Matplotlib
* Creacion de funciones
* Alcance local y global de las variables
  
## En que consiste el proyecto?
Durante este desafío, se ayudara al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, se analizará datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. *El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.*

## Como ejecutar mi proyecto?
1.Clona este repositorio o descarga el notebook AluraStoreLatam.ipynb.

2.Ejecuta cada celda en orden para realizar el análisis completo.

3.Asegúrate de tener conexión a internet, ya que los datos se cargan desde URLs

## Explicacion resumida del analisis que realice:
**1. Crear un diccionario de las tiendas y sus valores**
     Cree un diccionario llamado *Tiendas*, donde sus llaves son:
     'Tienda1', 
     'Tienda2', 
     'Tienda3' y 
     'Tienda4',
     donde sus valores son los elementos de los Pandas

**2. Sacar el ingreso total (facturacion) de cada tienda, de acuerdo a todas sus ventas**
     Cree un diccionario llamado *"ingresos_por_tienda"* 
     Utilice un bucle for para acceder a los datos de las ventas de cada tienda
     para despues usar la funcion .sum() para sumar los datos
     
**3. Clasificar las categorias mas y menos vendidas de cada tienda** 
     Cree un diccionario llamado *"mayor_categoria_ventas"* y otro llamado *"menor_categoria_ventas"*
     Utilice un bucle for para acceder a los datos de la categoria de cada venta.
     despues utilice la funcion .value_counts para contar cuantas veces se repetia una categoria.
     de ultimo utilice la funcion .idmax() y .idmin() para encontrar las categorias mas y menos vendidas de cada tienda
     
**4. Valoracion Media por tienda**
     Cree un diccionario llamado *"Calificacion_promedio"*
     Utilice el bucle for para acceder a los datos de calificacion de cada tienda.
     despues use la funcion .mean() para sacar el promedio de calificaciones

**5. Productos mas y menos vendidos de cada tienda**
     Cree un diccionario llamado *"Producto_mas_vendidos"* y otro llamado *"Producto_menos_vendidos"*
     Utilice el bucle for para acceder a los datos del nombre de los productos vendidos de cada tienda.
     despues utilice la funcion .value_counts para contar cuantas veces se repetia la venta de un producto
     y de ultimo use la funcion .idmax(5) y .idmin(5) para encontrar el top 5 productos mas y menos vendidos

**6. Valor promedio por envio**
     Cree un diccionario llamado *"Envio_promedio"*
     Accedi a los datos de envio de cada tienda con el bucle for
     despues utilice la funcion .mean() para sacar el promedio de costo de envio
     


