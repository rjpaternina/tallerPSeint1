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
        Leer edad;
        Escribir 'Digite su estatura';
        Leer estatura;

      FinAlgoritmo




3) Realizar un programa el cual solicite su nombre y apellidos, también debe capturar nombre y apellidos de su padre y madre. Al finalizar debe imprimir en pantalla el    siguiente mensaje "Yo [Nombre Completo], soy hijo de [Nombre de la Madre] y [Nombre del Padre].

      Algoritmo otrosDatosPersonales
	
        Definir nombre, apellidos, nombrePadre, nombreMadre, apellidosPadre, ApellidosMadre Como Caracter;

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
      	Escribir 'La ciudad ', capital, ', ', ' es la capital del pais ', pais, '.';

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
	      Escribir '¿Cuantos años tiene ', nombreMascota, '?';
	      Leer edadMascota;
	      Escribir nombreMascota, ' es un(a) ', tipoMascota, ', el cual, tiene ', edadMascota, ' años de edad y ', nombreCompleto, ' es actualmente su dueño.';

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

	Algoritmo alquilerPeliculas
	
		//DEFINICION DE VARIABLES
		Definir eleccionUsuario Como Entero;
		Definir nombrePelicula, apreciacionesUsuario Como Caracter;
		Definir alquilarPelicula, anotacionesPelicula como logico;
		alquilarPelicula <- Falso;
		anotacionesPelicula <- Falso;
		
		//INICIO DE MENU
		Escribir "Bienvenido señor(a) usuario(a)";
		Escribir "Menú de usuarios:";
		Escribir  " 1 - Consultar pelicula";
		Escribir  " 2 - Alquilar pelicula";
		Escribir  " 3 - Devolver pelicula";
		Escribir  "Escoja una opcion 1-3:";
		Leer eleccionUsuario;
		Limpiar Pantalla;
		
		Segun eleccionUsuario Hacer
			1:
				//OPCION CONSULTAR PELICULA
				Escribir "Digite nombre de pelicula a buscar";
				Leer nombrePelicula;
				Escribir "La pelicula buscada es:", nombrePelicula;
				Escribir "Desea alquilarla? - (Digite: Falso o Verdadero)";
				Leer alquilarPelicula;
				Si alquilarPelicula = Verdadero Entonces
					Escribir "Es un gusto, ya se la traemos!";
				SiNo
					Escribir "A la orden, fue un placer atenderlo!";
				FinSi
			2:
				//OPCION CONSULTAR PELICULA
				Escribir "Digite nombre de pelicula a alquilar";
				Leer nombrePelicula;
				Escribir "Es un gusto, ya se la traemos!";
				
			3:		
				//OPCION DEVOLVER PELICULA
				Escribir "Desea realizar alguna anotacion o novedad sobre la pelicula devuelta? (Digite Falso o Verdadero)";
				Leer anotacionesPelicula;
				Limpiar Pantalla;//OPCION DEVOLVER PELICULA
				Si anotacionesPelicula = Verdadero Entonces
					Escribir "Apreciado(a) usuario(a), favor diligenciar sus apreciaciones o novedades acerca de la pelicula devuelta:";
					Leer apreciacionesUsuario;
					Limpiar Pantalla;
					Escribir "Señor(a) usuario(a), sus apreciaciones fueron procesada satisfactoriamente. Ha sido un gusto atenderlo!";
				SiNo
				   Escribir "Fue un placer atenderlo";
				FinSi
				
			De Otro Modo:
				Escribir "Favor, elegir entre las opciones presentadas.";
		FinSegun
	FinAlgoritmo

5.	La Droguería Mi Salud presta sus servicios en la localidad de Suba y requiere una aplicación para poder facturar los productos que vende a sus clientes y para ello, los productos tienen unas características que deben indicársele al cliente para que pueda escoger el producto a comprar. Para cada cliente, se tienen las opciones de compra de producto, consulta de precios por producto y devoluciones en caso de que se presenten.

	Algoritmo appDrogueria
		
		//DEFINICION DE VARIABLES
		Definir eleccionUsuario, opcionDevolucion Como Entero;
		Definir nombreProducto, devolucionPoducto Como Caracter;
		Definir comprarProducto como logico;

		comprarProducto <- Falso;

		//INICIO DE MENU
		Escribir "Bienvenido señor(a) usuario(a)";
		Escribir "Menú de usuarios:";
		Escribir  " 1 - Consultar precio de producto";
		Escribir  " 2 - Comprar producto";
		Escribir  " 3 - Devolver producto";
		Escribir  "Escoja una opcion 1-3:";
		Leer eleccionUsuario;

		Segun eleccionUsuario Hacer
			1:
				//OPCION CONCULTAR PERIO DE PRODUCTO
				Escribir "Digite nombre de producto";
				Leer nombreProducto;
				Escribir "El producto elegido es:", nombreProducto;
				Escribir "Desea comprar el producto? (Digite Falso o Verdadero)";
				Leer comprarProducto;
				Si  comprarProducto = Verdadero Entonces
					Escribir "Es un gusto, ya se la traemos!";
				SiNo
					Escribir "Recuerde que siempre estamos a la orden para cuando quiera adquirirlo!";
				FinSi
				
			2:	
				//OPCION COMPRAR PRODUCTO
				Escribir "Digite nombre de producto";
				Leer nombreProducto;
				Escribir "Es un gusto, ya se la traemos!";
				
			3:	
				//OPCION DEVOLVER PRODUCTO
				Escribir "Señor(a) usuario(a), favor diligenciar el motivo de devolucion del producto";
				Leer devolucionPoducto;
				Escribir "Señor(a) usuario(a), que desea hacer? Elija una opcion: 1 - Reposición de producto 2 - 				 				 Devolución de producto";
				Leer opcionDevolucion;
				Si opcionDevolucion = 1 Entonces
						Escribir "Señor(a) usuario(a), ya procederemos con su reposicion";
				SiNo
					Si opcionDevolucion = 2 Entonces
						Escribir "Señor(a) usuario(a), ya procederemos con la devolución de su dinero";
					SiNo
						Escribir "Señor(a) usuario(a), la opción elegida no es válida, favor elegir una de 						   las opciones presentadas";
					FinSi

				FinSi
				
			De Otro Modo:
				Escribir "Señor(a) usuario(a), esta opcion no existe, favor elegir entre las opciones presentadas";
		FinSegun

	FinAlgoritmo

6.	El taller de motos "El Maquinista" recibe motocicletas de alto cilindraje para realizar las respectivas revisiones y requiere una aplicación que le permita registrar los servicios generados a sus clientes. Para cada motocicleta se debe tener registro del ingreso al taller y las observaciones por parte del cliente. También debe existir registro de salida del taller con las novedades y otra de arreglos hechos por el mecánico en caso de que se requiera inventariar cambios repuestos en la motocicleta al entregarla.

	Algoritmo tallerMoto

		Definir nombreCliente, apellidoCliente, DNI, direccionCliente, telCliente, emailCliente, marcaMoto, cilindrajeMoto, mtto, observacionCliente,          		       serviciosPrestados, repuestosVendidos, serviciosYRptos, servicioConforme, servicioNoConforme Como Caracter;
		Definir eleccionUsuario, tipoMtto, conceptoFactura, motivoSalida Como Entero;
		Definir valorServicios, valorRepuestos, valorServiciosYRepuestos, totalFacturacion Como Real;

		Escribir "***Taller de motos El Maquinista***";
		Escribir "Menú de usuarios:";
		Escribir  " 1 - Registrar Cliente";
		Escribir  " 2 - Ingreso a Taller";
		Escribir  " 3 - Facturar Ventas y/o Servicios";
		Escribir  " 4 - Salida de Taller";
		Escribir  "Escoja una opcion 1-4:";
		Leer eleccionUsuario;
		Limpiar Pantalla;

		Segun eleccionUsuario Hacer
			1: 
				//OPCION 1 - REGISTRAR CLIENTES
				Escribir "Digite nombres del cliente:";
				Leer nombreCliente;
				Escribir "Digite apellidos del cliente:";
				Leer apellidoCliente;
				Escribir "Digite DNI cliente:";
				Leer DNI;
				Escribir "Digite direccion del cliente:";
				Leer direccionCliente;
				Escribir "Digite telefono del cliente:";
				Leer telCliente;
				Escribir "Digite su correo electronico:";
				Leer emailCliente;
				Limpiar Pantalla;
				Escribir "El cliente registrado es: ", nombreCliente,  " , ", apellidoCliente, " , ", "DNI: ", DNI, " , ", "Direccion: ", 					direccionCliente, " , ", "Telefono: ", telCliente, " , ", "Correo electronico: ", emailCliente;
			
			2:	
				//OPCION 2 - INGRESO A TALLER
				Escribir "Digite marca de moto:";
				Leer marcaMoto;
				Escribir "Digite modelo:";
				Leer modeloMoto;
				Escribir "Digite cilindraje (cc):";
				Leer cilindrajeMoto;
				Escribir "Digite numero de placa:";
				Leer placaMoto;
				Limpiar Pantalla;
				Escribir "Motivo de ingreso a taller: 1 - Mantenimiento preventivo o 2 - Mantenimiento correctivo";
				Leer tipoMtto;
				Si tipoMtto = 1 Entonces
					mtto <- "preventivo"
				SiNo
					Si tipoMtto = 2 Entonces
						mtto <- "correctivo"
					FinSi
				FinSi
				Escribir "Registre las observaciones del cliente:";
				Leer observacionCliente;
				Limpiar Pantalla;
				Escribir "***ENTRADA A TALLER***";
				Escribir "**Datos de ingreso de la moto**  - ", "Marca moto: ", marcaMoto, " ; ", "Modelo: ", modeloMoto, " ; ",  "Cilindraje (cc): ", 				       cilindrajeMoto, " ; ",  "Placa: ", placaMoto, " ; ", "Motivo de ingreso: Mantenimiento ", mtto, " ; ";
				Escribir "Motivos de ingreso y/o observaciones del cliente: ", observacionCliente;
				
			3:	
				//OPCION 3 - FACTURAR VENTAS Y SERVICIOS
				Escribir "Menú Facturacion";
				Escribir "Concepto a facturar:";
				Escribir " 1 - Servicio";
				Escribir " 2 - Repuestos";
				Escribir " 3 - Servicio + respuestos";
				Leer conceptoFactura;

				Si conceptoFactura = 1 Entonces
					Escribir "Digite los servicios prestados:";
					Leer serviciosPrestados;
					Escribir "Digite el valor de los servicios prestados:";
					Leer valorServicios;
					Limpiar Pantalla;
					Escribir "Los servicios prestados son: ", serviciosPrestados, " por un total de ",  valorServicios, " pesos.";

				SiNo
					Si conceptoFactura = 2 Entonces
						Escribir "Digite los repuestos vendidos:";
						Leer repuestosVendidos;
						Escribir "Digite el valor de repuestos vendidos:";
						Leer valorRepuestos;
						Limpiar Pantalla;
						Escribir "Los repuestos vendidos son: ", repuestosVendidos, " por un total de ",  valorRepuestos, " pesos.";
					SiNo
						Si conceptoFactura = 3 Entonces
							Escribir "Digite los servicios prestados y repuestos vendidos:";
							Leer serviciosYRptos;
							Escribir "Digite el valor de servicios y repuestos vendidos:";
							Leer valorServiciosYRepuestos;
							Limpiar Pantalla;
							Escribir "Los servicios prestados y repuestos vendidos son: ",  serviciosYRptos, " por un total de ",  								valorServiciosYRepuestos, " pesos.";
						FinSi
					FinSi
				FinSi
				totalFacturacion <- valorServicios + valorRepuestos + valorServiciosYRepuestos;
				Escribir "El total de su factura por servicios prestados y/o repuestos vendidos son: ", serviciosPrestados, repuestosVendidos, 					serviciosYRptos, " por un total de ",  totalFacturacion, " pesos.";	

			4:
				//OPCION 4- SALIDA DE TALLER
				Escribir "Digite marca de moto:";
				Leer marcaMoto;
				Escribir "Digite modelo:";
				Leer modeloMoto;
				Escribir "Digite cilindraje:";
				Leer cilindrajeMoto;
				Escribir "Digite numero de placa:";
				Leer placaMoto;
				Escribir "Motivo de salida de taller: 1 - Servicio conforme o 2 - Servicio no conforme";
				Leer motivoSalida;
				Si motivoSalida = 1 Entonces
					Escribir "Relaciones los servicios prestados,  repuestos consumidos en reparacion de la moto y otras observaciones de 						conformidad:";
					Leer servicioConforme;
					Limpiar Pantalla;
					Escribir "***SALIDA DE TALLER***";
					Escribir "Se hace entrega de moto", " ", marcaMoto, ", ", "modelo ", modeloMoto, ", ",  "cilindraje ", cilindrajeMoto, "cc ", 					      ", ",  "placa ", placaMoto, " con las siguientes observaciones: ", servicioConforme;   
				SiNo
					Si motivoSalida = 2 Entonces
						Escribir "Relacione las razones de la no conformidad del servico y otras observaciones:";
						Leer servicioNoConforme;
						Limpiar Pantalla;
						Escribir "***SALIDA DE TALLER***";
						Escribir "Se hace entrega de moto", " ", marcaMoto, ", ", "modelo ", modeloMoto, ", ",  "cilindraje ", cilindrajeMoto, 						       "cc", ", ",  "Placa ", placaMoto, " con las siguientes observaciones de no conformidad: ", servicioNoConforme;   
					FinSi
				FinSi
			De Otro Modo:
				Escribir "Favor seleccionar de las opciones presentadas";
		FinSegun
	FinAlgoritmo


7.	La Secretaría de Salud Municipal requiere de una aplicación que le permita calcular el IMC (Índice de masa corporal) y requiere los datos peso en kilogramos y estatura en metros Para cada persona encuestada adicional a los datos suministrados, debe mostrar el resultado para cada uno y establecer en qué rango se encuentra (bajo peso, normal, sobrepeso y obeso).

	Algoritmo masaCorporal

		Definir IMC, peso, estatura Como Real;

		Escribir "Señor usuario(a), digite su peso en kilogramos:";
		Leer peso;
		Escribir "Señor usuario(a), digite su estatura en metros:";
		Leer estatura;

		IMC <- peso / (estatura * estatura);
		Si IMC < 18.5  Entonces
			Escribir "Usted se encuentra en un rango bajo de peso";
		SiNo
			Si (IMC > 18.4) y (IMC < 25) Entonces
				Escribir "Usted se encuentra en un rango normal de peso";
			SiNo
				Si (IMC > 24.9) y (IMC < 30) Entonces
					Escribir "Usted seencuentra en un rango de sobrepeso";
				SiNo
					Si (IMC >= 30) Entonces
						Escribir "Usted se encuentra en un rango de obeso";
					FinSi
				FinSi

			FinSi
		FinSi


	FinAlgoritmo


8.	El pastelero Don Carlos es el mejor pastelero de la ciudad y requiere una aplicación que le permita registrar los pedidos de los clientes en cuanto a las tortas que realiza. Cada torta tiene unas características propias como sabor, cantidad (porciones) y decoraciones). Se requiere que la aplicación permita registrar los pedidos, las tortas disponibles y las ventas que se registren diariamente.

9.	El profesor de geometría está explicando a sus estudiantes las fórmulas para calcular el área de diferentes figuras geométricas, para ello requiere una aplicación que le facilite el ejercicio solicitándole los valores al estudiante. La aplicación debe permitir que el estudiante seleccione si desea calcular el área de un rectángulo, triángulo o trapecio. No olvide solicitar los datos necesarios para realizar cada cálculo y mostrar su respectivo resultado.

10.	El banco "Su banco fiel" es un banco que inicia sus actividades financieras y necesita una aplicación para llevar las cuentas de sus usuarios; por lo tanto, se sugiere que la cuenta tenga los atributos titular y cantidad. Para cada cliente las cuentas permitirán realizar ingresos, retiros o consultas de valor. En los ingresos no se pueden insertar valores negativos y para los retiros el valor no puede ser mayor al valor que tiene en la cuenta.
