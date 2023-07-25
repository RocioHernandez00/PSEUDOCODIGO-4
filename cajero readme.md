``` pcs Funcion balance <- cashier ()
	Definir balance Como Real;
	balance = 1000;
	Repetir
		Imprimir "Selecciona una opción:";
		Imprimir "a. Depositar.";
		Imprimir "b. Retirar.";
		Imprimir "c. Salir.";
		leer option
		Si option = 'a' Entonces
			balance = balance + deposit()
		FinSi
		Si option = 'b' Entonces
			balance = balance - retirar()
		FinSi
	Mientras Que option = "a" | option = "b"
Fin Funcion

Funcion valor <- deposit()
	Imprimir "¿Cuánto deseas depositar?:";
	leer valor
FinFuncion

Funcion valor <- retirar()
	Imprimir "¿Cuánto deseas retirar?:";
	leer valor
FinFuncion

Algoritmo exampleCashier
	Imprimir cashier()
FinAlgoritmo
