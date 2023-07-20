``` pcs Algoritmo lanzarMoneda
	
	Escribir "Ingresa el nombre del primer jugador"
	leer player1
	Escribir "Ingresa la cantidad a jugar"
	leer monto1
	Escribir "Ingresa el nombre del segundo jugador"
	leer monto2
	Escribir "Ingresa la cantidad a jugar"
	leer monto2
	
	SI monto1<=0 | monto2 <=0 Entonces
		SI monto1<=0 & monto2 <=0 Entonces
			Imprimir "Juego Cancelado"
		SiNo
			SI monto1<=0 Entonces
				Imprimir "Jugador que gana: ", Mayusculas(player2), " cantidad ganada: 0"
			SiNo
				Imprimir "Jugador que gana: ", Mayusculas(player1), " cantidad ganada: 0"
			FinSi
		FinSi
	SiNo
		SI Aleatorio(1,2) = 1 Entonces
			Imprimir "Jugador que gana: ", Mayusculas(player1), " cantidad ganada: ", monto2
		SiNo
			Imprimir "Jugador que gana: ", Mayusculas(player2), " cantidad ganada: ", monto1
		FinSi
	FinSi
