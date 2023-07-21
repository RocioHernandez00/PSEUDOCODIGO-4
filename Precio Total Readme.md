``` pcs Funcion valor <- TotalPrecio (precio, iva)
	Definir valor Como Real;
	SI precio > 3000 Entonces
		valor = ( precio + (precio/100*iva) ) / 100*90
	SiNo
		valor = ( precio + (precio/100*iva) )
	FinSi
Fin Funcion

Algoritmo ejemplo_TotalPrecio
	Imprimir TotalPrecio(5000,21)
FinAlgoritmo
