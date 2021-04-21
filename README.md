# Tarea_colaborativa_Cortes_Aguilera_Javier-F.
//Calcula el promerdio de una Lista de N datos
Algoritmo Promedio

	Definir b como caracter
	definir acum Como Entero
	definir prom Como Real
	definir dato como Entero
  
	Repetir
		Escribir "Ingrese la cantidad de datos:"
		leer n
		
		Si n>0 Entonces
			Para i<-1 Hasta n Hacer
				Escribir "Ingrese el dato ",i,":"
				Leer dato
				acum<-acum+dato
			FinPara
		SiNo
			Repetir
				Escribir "El número es negativo. Debe insertar un nº positivo"
				Leer n;
				Si n<0 Entonces
					
				FinSi
			Hasta Que n>0
			Escribir "Correcto. "
			
			acum<-0
			 
			Para i<-1 Hasta n Hacer
				Escribir "Ingrese el dato ",i,":"
				Leer dato
				acum<-acum+dato
				
			FinPara
		FinSi
		
		
		prom<-acum/n
		
		Escribir "El promedio es : ",prom
		Escribir "¿Desea continuar? Ingrese s para si,";
		Leer b;
	Mientras que b= "s" o b= "S"
		
FinAlgoritmo
