* Objetos: Los objetos almacenan una cantidad de cajas que yo quiera y con el nombre que yo quiera para acceder a la caja simplemente me refiera a ella por su nombre.
a diferencia de los arrays no nececito saber la ubicacion numerica de la caja simplemente digo que caja quiero abrir.

* Propiedades: Una propiedad seria en el caso de los objetos el nombre de la caja y el interior de la caja. por ejemplo adentro del objeto "Datos de henry" hay una caja llamada "Nombre" y tiene adentro "Henry" en este caso la asociacion "Nombre henry" es una propiedad del objeto "Datos de henry".

* Métodos: Si abro una caja que esta dentro de un objeto y esa caja abre una funcion esa caja es un metodo que seria igual a una propiedad solo que tiene adentro una funcion.

* Bucle `for…in`: Se usa como una estructura for para recorrer un array, pero los objetos a diferencia de los arrays no estan ordenados por numeros si no con nombres el bucle for in permite recorrer todas las propiedades del objeto.

* Notación de puntos vs notación de corchetes:

  -Notacion por puntos:

    Ventajas: Mas facil de escribir.
    Desventajas: Despues del punto no se pueden poner variables. literalmente se tiene que poner la llave de la propiedad es decir el nombre de la caja.

      ejemplo:
      var i = "NOMBRE DE LA CAJA"
      OBJETO.i = undefine // esta mal
      OBJETO."NOMBRE DE LA CAJA" = "LO QUE ESTA ADENTRO DE LA CAJA" // esta bien

  -Notacion por corchetes:

    Desventajas: Mas lento de escribir.
    Ventajas: Mas usos.

      ejemplo:
      var i = "NOMBRE DE LA CAJA"
      OBJETO [i] = "LO QUE ESTA ADENTRO DE LA CAJA" // esta bien
      OBJETO ["NOMBRE DE LA CAJA"] = "LO QUE ESTA ADENTRO DE LA CAJA" // esta bien
