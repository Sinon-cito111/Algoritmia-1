# Algoritmo en PSeInt: Cómo preparar un buen tinto

Este documento muestra el paso a paso estructurado como un algoritmo en PSeInt para simular la preparación de un tinto tradicional.

## Código en PSeInt

```pseint
Algoritmo HacerTinto
	Definir cantidadAgua Como Real
	Definir respuestaAzucar Como Cadena
	
	Escribir "=== SIMULADOR: CÓMO PREPARAR UN TINTO ==="
	Escribir "Paso 1: ¿Cuántas tazas de agua vas a preparar?"
	Leer cantidadAgua
	
	Escribir "Paso 2: Colocar la olla o cafetera con ", cantidadAgua, " tazas de agua en la estufa."
	Escribir "Paso 3: Encender el fuego y esperar a que el agua hierva..."
	
	Escribir "Paso 4: ¿Deseas agregar panela o azúcar al agua? (S/N)"
	Leer respuestaAzucar
	
	Si respuestaAzucar == "S" O respuestaAzucar == "s" Entonces
		Escribir "-> Añadir panela o azúcar al gusto y revolver hasta disolver."
	FinSi
	
	Escribir "Paso 5: Agregar el café molido (1 cucharada por taza aprox.) en el filtro o recipiente."
	Escribir "Paso 6: Verter el agua caliente sobre el café lentamente."
	Escribir "Paso 7: Servir el tinto caliente en una taza. ¡Listo para disfrutar!"
	
FinAlgoritmo
```