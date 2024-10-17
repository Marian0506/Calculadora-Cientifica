# Calculadora-Cientifica
Algoritmo Calculadora 
	//Calculadora Basica
		Definir opcion, num1, num2, resultado Como Real
		Escribir "Calculadora Básica"
		Escribir "Seleccione una operación:"
		Escribir "1. Suma"
		Escribir "2. Resta"
		Escribir "3. Multiplicación"
		Escribir "4. División"
		Leer opcion
		
		Escribir "Ingrese el primer número:"
		Leer num1
		Escribir "Ingrese el segundo número:"
		Leer num2
		
		Segun opcion Hacer
			Caso 1:
				resultado <- num1 + num2
				Escribir "El resultado de la suma es: ", resultado
			Caso 2:
				resultado <- num1 - num2
				Escribir "El resultado de la resta es: ", resultado
			Caso 3:
				resultado <- num1 * num2
				Escribir "El resultado de la multiplicación es: ", resultado
			Caso 4:
				Si num2 <> 0 Entonces
					resultado <- num1 / num2
					Escribir "El resultado de la división es: ", resultado
				SiNo
					Escribir "Error: No se puede dividir entre cero."
				FinSi
		
				Escribir "Opción no válida."
		FinSegun

FinAlgoritmo
