**Archivo Leeme**

PROYECTO CALCULADORA:

Product Backlog:

- Resultado de suma de 2 núm. naturales
- Resultado de multiplicar 2 núm. naturales
- Resultado de restar 2 núm. naturales (feedback al usuario incluido).
- Notacion en numeros romanos (opcional pero se va a realizar).

SPRINT: (El equipo se siente fuerte, incluimos en el sprint ¡todo el backlog!)

Prioridad	Historia    Tareas	Estimación t      Historia completa cuando...

1		Suma 				3		Suma correcta
			TDD-Test unit.		1
			codificar suma		1
			Prueba y Refactorizar	1
	
2		Multiplicar			3		Multiplicación correcta
			TDD-Test unit.		1
			codificar mult.		1
			Prueba y Refactorizar	1
	
3		Restar				4		Restar y emitir feedback correctamente 
			TDD-Test unit.		1
			codificar resto		1
			codificar feedback	1
			Prueba y Refactorizar	1
			
4		Notación números romanos	3		La notación tiene que estar debidamente
			TDD-Test unit.		1		implementada
			codificar notación	1
			Prueba y Refactorizar	1	

				
**Comentarios:**


El feedback del error al usuario en caso de equivocarse en la resta, 
se ha incluido como tarea dentro de la historia de usuario de la resta.

Al considerar recursos ilimitados, dividiremos las historias para que
diferentes programadores realicen tareas en paralelo. Las historias de usuario
de prioridad 1, 2 y 3 se pueden trabajar de forma independiente, no son bloqueantes
entre sí, pero sí lo son las tareas que contienen cada historia entre sí.

Una vez se terminen, realizamos la 4, de menor prioridad y bloqueada
por las demás tareas, ya que es necesario  para que traduzca la notación a números romanos.

