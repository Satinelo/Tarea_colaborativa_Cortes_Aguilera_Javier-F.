# Tarea_colaborativa_Cortes_Aguilera_Javier-F.
// Calcula el promerdio de una Lista de N datos
Algoritmo Promedio
	
	Definir b como caracter
	definir acum Como Entero
	definir prom Como Real
	definir dato como Entero
	
	Repetir
		
		Escribir "Ingrese la cantidad de datos:"
		leer n
		acum<-0
		Si n>0 Entonces
			escribir "El numero es positivo"
			Para i<-1 Hasta n Hacer
				Escribir "Ingrese el dato", i, ":"
				Leer dato
				acum <-acum + dato
			FinPara
		SiNo
			Repetir
				Escribir "El número es negativo. Debe insertar un nº positivo"
				Leer n;
				Si n<0 Entonces
					
				FinSi
			Hasta Que n> 0
			Escribir "Correcto"
			leer n 
			
			acum <-0
			
			Para i <-1 Hasta n Hacer
				Escribir "Ingrese el dato", i, ":"
				Leer dato
				acum <-acum + dato
				
			FinPara
		FinSi
		
		
		prom <-acum / n
		
		Escribir "El promedio es:", prom
		Escribir "¿Desea continuar? Ingrese n para finalizar, s para continuar"
		Leer b 
		
	Hasta que b= "n"
	
FinAlgoritmo

