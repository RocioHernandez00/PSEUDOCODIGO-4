``` pcs Funcion resultado <- convertidorDeTiempo (number)
	Definir resultado Como Caracter;
	Definir dias, horas, minutos, segundos Como Entero;
	segundos = number % 60;
	minutos = Trunc(number/60) % 60;
	horas = Trunc(number/3600) % 24;
	dias = Trunc(number/86400);
	resultado = Concatenar('dias: ', ConvertirATexto(dias));
	resultado = Concatenar(resultado, ', horas: ');
	resultado = Concatenar(resultado, ConvertirATexto(horas));
	resultado = Concatenar(resultado, ', minutes: ');
	resultado = Concatenar(resultado, ConvertirATexto(minutos));
	resultado = Concatenar(resultado, ', y segundos: ');
	resultado = Concatenar(resultado, ConvertirATexto(segundos));
Fin Funcion

Algoritmo ejemploConvertidorDeTiempo
	Imprimir convertidorDeTiempo(100000)
FinAlgoritmo
