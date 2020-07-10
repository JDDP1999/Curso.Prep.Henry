* `prototype` : En JS todos son objetos y cada objeto tiene su prototipo que es su clase, que sirven para cargar sus metodos, es decir para configurar sus usos.
* _Constructors_ (de Clases): Es un tipo de funcion que sirve para crear objetos y no estar repitiendo las keys,por convencion al invocarlas su primera letra es una mayuscula.
Ejemplo:

function Persona (nombre,apellido,edad) { this.nombre = nombre; this.apellido = apellido; this.edad = edad; }; 
Jonathan = new Persona ("Jonathan","Davis","21");
Persona { nombre: 'Jonathan', apellido: 'Davis', edad: 21 } 
Ioel = new Persona ("Ieol","Davis","12");
Persona { nombre: 'Ieol', apellido: 'Davis', edad: 12 }// Asi de facil cree 2 objetos, con la funcion construct.
