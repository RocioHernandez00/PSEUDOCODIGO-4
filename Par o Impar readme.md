``` pcs Algoritmo paroImpar
	Repetir
		Escribir "escribe un numero entre 1 y 50"
		leer num
		si num < 1 | num > 50 Entonces
			Imprimir "numero invalido"
			
		FinSi
	Mientras Que num <1 | num  >50
	par = num % 2 = 0
	
	para count=1 Hasta num Con Paso 1 Hacer
		si count % 2 = 0 & par Entonces
			imprimir count
		FinSi
		si count  % 2 = 1 & ~ (par) Entonces
			Imprimir count
		FinSi
	FinPara
		
	
	
FinAlgoritmo
