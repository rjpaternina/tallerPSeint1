# tallerPSeint
Taller de PSeInt #1: Variables e impresión

A continuación se describirán los ejercicios que deberá realizar. Por favor guardar los ejercicios dado que serán requeridos en entregas posteriores. Todos los ejercicios deben estar escritos en PSeInt con el perfil Estricto.

1) Realizar un programa el cual solicite su nombre y apellidos

      Algoritmo nombre_Apellidos

        Definir nombre, apellidos Como Caracter;

        Escribir 'Digite su nombre: ";
        Leer nombre;
        Escribir 'Digite sus apellidos: ';
        leer apellidos;

      FinAlgoritmo


2) Realizar un programa el cual solicite su nombre, apellidos, edad y estatura.

      Algoritmo datosPersonales

        Definir nombre, apellidos Como Caracter;
        Definir edad Como Entero;
        Definir estatura Como Real;

        Escribir 'Digite su nombre: ";
        Leer nombre;
        Escribir 'Digite sus apellidos: ';
        leer apellidos;
        Escribir 'Digite su edad';
        Leer edad
        Escribir 'Digite su estatura';
        Leer estatura;

      FinAlgoritmo




3) Realizar un programa el cual solicite su nombre y apellidos, también debe capturar nombre y apellidos de su padre y madre. Al finalizar debe imprimir en pantalla el    siguiente mensaje "Yo [Nombre Completo], soy hijo de [Nombre de la Madre] y [Nombre del Padre].

      Algoritmo otrosDatosPersonales
	
        Definir nombre, nombrePadre, nombreMadre, apellidosPadre, ApellidosMadre Como Caracter;

        Escribir 'Digite su nombre: ";
        Leer nombre;
        Escribir 'Digite sus apellidos: ';
        leer apellidos;
        Escribir 'Digite nombre de su padre: ";
        Leer nombrePadre;
        Escribir 'Digite los apellidos de su padre: ';
        Leer apellidosPadre;
        Escribir 'Digite nombre de su Madre: ";
        Leer nombreMadre;
        Escribir 'Digite apellidos de su madre: ";
        leer ApellidosMadre;
        Escribir 'Yo ', nombre, ' ', apellidos, ',', ' soy hijo de ', nombreMadre, ' y ', nombrePadre, '.';

      FinAlgoritmo



4) Realizar un programa el cual solicite el nombre de una ciudad capital y el país. Al finalizar debe imprimir en pantalla el siguiente mensaje "La ciudad [Nombre de      la Ciudad], es la capital del país [Nombre del País]

      Algoritmo capitalPais

      	Definir capital, pais Como Caracter;

      	Escribir 'Ingrese el nombre de un pais: ';
      	Leer pais;
      	Escribir 'Ingrese la capital de ', pais;
      	Leer capital;
      	Escribir 'La ciudad ', capital, ', ' ' es la capital del pais ', pais, '.';

     FinAlgoritmo



5) Realizar un programa el cual solicite el nombre de su mascota, edad de la mascota, el tipo de mascota y su nombre completo. Al finalizar el sistema debe e imprimir    en pantalla el siguiente mensaje: [Nombre de Mascota] es un(a) [Tipo de Mascota], el cual, tiene [Edad de la Mascota] años de edad y [Nombre Completo] es              actualmente su dueño(a).

	Algoritmo mascota
	
	      Definir nombreCompleto, nombreMascota, tipoMascota Como Caracter;
	      Definir edadMascota Como Entero;

	      Escribir 'Ingrese su nombre completo: ';
	      Leer nombreCompleto;
	      Escribir '¿Como se llama su mascota?';
	      Leer nombreMascota;
	      Escribir '¿Que tipo de mascota es?';
	      Leer tipoMascota;
	      Escribir '¿Cuantos años tiene ' nombreMascota, '?';
	      Leer edadMascota;
	      Escribir nombreMascota, ' es un(a) ', tipoMascota, ', el cual, tiene ', edadMascota, ' años de edad y ' nombreCompleto, ' es actualmente su dueño.';

   	FinAlgoritmo


Taller#2 - Taller de condicionales

A continuación se describirán los ejercicios que deberá realizar. Por favor guardar los ejercicios dado que serán requeridos en entregas posteriores. Todos los ejercicios deben estar escritos en PSeInt con el perfil Estricto.

1.	Realizar un programa en el cual se solicite la edad de una persona. Si la persona es mayor o igual a 18 años, deberá mostrar en pantalla: Usted es mayor de edad.
	
	Algoritmo edadPersona;

		Definir edad como entero;

		Escribir "Digite su edad";
		Leer edad;
		Si edad >= 18 Entonces
			Escribir "Usted es mayor de edad";
		FinSi
	
	FinAlgoritmo;



2.	Realizar un programa en el cual se solicite la edad de una persona. Si la persona es menor a 18 años, deberá mostrar en pantalla: Usted aún es un niño(a).

	Algoritmo edadMenor;
	
		Definir edad como entero;

		Escribir "Digite su edad";
		Leer edad;
		Si edad < 18 Entonces
			Escribir "Usted aún es un niño(a)";
		FinSi
	
	FinAlgoritmo;
	

3.	Realizar un programa en el cual se solicite el nombre, apellidos y edad de la persona. Si la persona es mayor o igual a 18 años, entonce se deberá imprimir en pantalla [Nombre completo] usted es mayor de edad, por lo tanto puede entrar a la fiesta. Si la edad de la persona es menor que 18 años, entonces, deberá imprimirse el siguiente mensaje: [Nombre completo] usted es menor de edad, por lo tanto, no puede entrar a la fiesta, por favor devuélvase a su casa.

	Algoritmo entradaFiesta;
	
		Definir nombre, apellidos Como Caracter;
		Definir edad Como Entero;

		Escribir "Digite su nombre:";
		Leer nombre;
		Escribir "Digite sus apellidos:";
		Leer apellidos;
		Escribir "¿Cual es su edad?";
		Leer edad;

		Si edad >= 18 Entonces
			Escribir nombre, " ", apellidos, ", usted es mayor de edad, por lo tanto puede entrar a la fiesta.";
		SiNo
			Escribir nombre, " ", apellidos, ", usted es menor de edad, por lo tanto, no puede entrar a la fiesta, por favor devuélvase a su casa.";
		FinSi

	FinAlgoritmo;
	

4.	La video tienda que presta sus servicios de alquiler de películas a los usuarios del barrio el Porvenir, requiere de una aplicación que permita registrar el alquiler de las películas que adquieren sus usuarios. Para cada usuario se debe permitir la opción de alquilar película, consultar películas disponibles y recibir película en la video tienda con la opción de realizar anotaciones sobre estas si se llegan a presentar daños u otra novedad sobre la película.

5.	La Droguería Mi Salud presta sus servicios en la localidad de Suba y requiere una aplicación para poder facturar los productos que vende a sus clientes y para ello, los productos tienen unas características que deben indicársele al cliente para que pueda escoger el producto a comprar. Para cada cliente, se tienen las opciones de compra de producto, consulta de precios por producto y devoluciones en caso de que se presenten.

6.	El taller de motos "El Maquinista" recibe motocicletas de alto cilindraje para realizar las respectivas revisiones y requiere una aplicación que le permita registrar los servicios generados a sus clientes. Para cada motocicleta se debe tener registro del ingreso al taller y las observaciones por parte del cliente. También debe existir registro de salida del taller con las novedades y otra de arreglos hechos por el mecánico en caso de que se requiera inventariar cambios repuestos en la motocicleta al entregarla.

7.	La Secretaría de Salud Municipal requiere de una aplicación que le permita calcular el IMC (Índice de masa corporal) y requiere los datos peso en kilogramos y estatura en metros Para cada persona encuestada adicional a los datos suministrados, debe mostrar el resultado para cada uno y establecer en qué rango se encuentra (bajo peso, normal, sobrepeso y obeso).

8.	El pastelero Don Carlos es el mejor pastelero de la ciudad y requiere una aplicación que le permita registrar los pedidos de los clientes en cuanto a las tortas que realiza. Cada torta tiene unas características propias como sabor, cantidad (porciones) y decoraciones). Se requiere que la aplicación permita registrar los pedidos, las tortas disponibles y las ventas que se registren diariamente.

9.	El profesor de geometría está explicando a sus estudiantes las fórmulas para calcular el área de diferentes figuras geométricas, para ello requiere una aplicación que le facilite el ejercicio solicitándole los valores al estudiante. La aplicación debe permitir que el estudiante seleccione si desea calcular el área de un rectángulo, triángulo o trapecio. No olvide solicitar los datos necesarios para realizar cada cálculo y mostrar su respectivo resultado.

10.	El banco "Su banco fiel" es un banco que inicia sus actividades financieras y necesita una aplicación para llevar las cuentas de sus usuarios; por lo tanto, se sugiere que la cuenta tenga los atributos titular y cantidad. Para cada cliente las cuentas permitirán realizar ingresos, retiros o consultas de valor. En los ingresos no se pueden insertar valores negativos y para los retiros el valor no puede ser mayor al valor que tiene en la cuenta.
