Algoritmo ejemplo_DireccionInversaYTamaño
	Imprimir DireccionInversaYTamaño("Hola Mundo")
FinAlgoritmo
Funcion resultado <- DireccionInversaYTamaño(texto)
	Definir resultado Como Caracter;
	resultado = "";
	Para count = Longitud(texto) Hasta 0 Con Paso -1 Hacer
		carta = Subcadena(texto,count,count);
		SI carta = Mayusculas(carta) Entonces
			carta = Minusculas(carta)
		SiNo
			carta = Mayusculas(carta)
		FinSi
		resultado = Concatenar(resultado, carta)
	FinPara
Fin Funcion
