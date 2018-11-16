Práctica Developer 2019
==========

Con esta interfaz se busca leer, mostrar y filtrar le información extraida de un archivo con datos (CSV).

Como ejecutar la aplicación
--------------------
La aplicacion es un archivo con extension .jar, por lo que es necesario tener instalado java para poder ejecutarlo, independiente del sistema operativo.
La ultima version de java se puede descargar en https://www.java.com/en/download/.

+ Para ejecutar en windows:  

    + Simplemente hacer dobleclick en el archivo Practica.jar

+ Para ejecutar en linux:

    + Abrir consola. 
    + Localizar e ir a la carpeta en la que se encuentra el archivo Practica.jar
    + Ejecutar el comando
      $ java -jar Practica.jar
     
Como utilizar la aplicación
--------------------

Una ves adentro veremos un grafico vacio, ya que aun no se ha cargado el archivo de datos, por lo que lo primero que debemos hacer es
+ Ir a la opción Abrir Archivo -> Buscar Archivo. 
+ Buscar el archivo con extención .csv en el computador.
+ Seleccionarlo y presionar Abrir.

Esto leera y graficara todos los datos por lo que puede tardar unos minutos.

Una ves cargado los datos se pueden utilizar las distintas opciones para el filtrado.

+ La opción "Compañías" permite seleccionar una compañia especifica y graficar solo los datos de dicha compañia. En caso de selccionar la opcion "Todas Las Compañias" se graficaran todos los datos.
+ La opción "Clientes" permite escribir el numero de ID de un cliente especifico y graficar solo los datos de dicho cliente. 
+ La opción "Periodo" permite variar la fecha inicial y fecha final en que se quiere visualizar el grafico.
+ La opcion "Intervalo Activo" permite modificar el valor del intervalo activo.

La unica forma de volver a visualizar todos los datos una ves aplicado algun filtro es con la opción Compañias -> Todas las Compañías

