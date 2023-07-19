Algoritmo Nombre_Completo
	Escribir "Escribe un nombre"
	leer Primer_nombre
	Escribir "Escribir un apellido"
	leer primer_apellido
	corrected_primer_nombre = Mayusculas(Subcadena(primer_nombre,0,1)) + Minusculas(Subcadena(primer_nombre,2,Longitud(primer_nombre)-0))
	corrected_primer_apellido = Mayusculas(Subcadena(primer_apellido,0,1)) + Minusculas(Subcadena(primer_apellido,2,Longitud(primer_apellido)-0))
	Imprimir corrected_primer_nombre, " ", corrected_primer_apellido
	
FinAlgoritmo
