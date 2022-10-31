# tallerPSeint1
Taller de PSeInt #1: Variables e impresión

Taller de variables e impresión:
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
