``` pcs Funcion resultado <- comparadorDeDistancia ()
	Definir resultado Como Logico;
	Definir NumeroNegativo, NumeroPositivo Como Real;
	NumeroNegativo = 0;
	NumeroPositivo = 0;
	Para count=1 Hasta 5 Con Paso 1 Hacer
		Escribir "Escribe un numero"
		leer num
		SI num > 0 Entonces
			NumeroPositivo = NumeroPositivo + num;
		SiNo
			NumeroNegativo = NumeroNegativo + num;
		FinSi
	FinPara
	resultado = NumeroPositivo > Abs(NumeroNegativo)
Fin Funcion

Algoritmo exampleCompareDistances
	Imprimir comparadorDeDistancia()
FinAlgoritmo
