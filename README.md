# Repositorio-de-prueba
Repositorio de prácticas
# Código en ensamblador
Se anexa el código ensamblador solicitado
Resultado EQU 0x2E0; Esta línea marca donde guardar el valor del resultado
MOV 	A, 5; Aquí marca donde almacenar el primer valor de la operación
MOV 	B, 4; Aquí se marca donde almacenar el segundo valor de la operación
MOV 	C, 0  ; Aquí se le da un valor de 0 a la celda donde guardar el resultado
ADD 	C, A  ;Aquí se suma el valor del registro 0 al primer valor, almacenando el resultado
ADD 	C, B  ; Aquí se suma el segundo valor al registro donde guardamos el resultado anterior 
MOV [Resultado], C; Se mueve la etiqueta de resultado al registro C del CPU
