# Ejercicio: ¡Adivina el Número!

## Descripción
Crea un programa en JavaScript que simule un juego de adivinar un número. El programa debe generar un número aleatorio entre 1 y 100, y luego permitir que el usuario intente adivinarlo utilizando un bucle `while`. El juego debe proporcionar pistas después de cada intento, como `"Muy alto"` o `"Muy bajo"`, hasta que el número sea adivinado correctamente.

## Instrucciones
1. Usa `Math.random()` para generar un número aleatorio entre 1 y 100 y guárdalo en una variable llamada `numeroSecreto`.
2. Crea una variable llamada `intento` para almacenar el número que el usuario adivina.
3. Usa un bucle `while` que se repita mientras el número ingresado por el usuario no sea igual al `numeroSecreto`.
4. Dentro del bucle:
   - Pide al usuario que ingrese un número utilizando `prompt()` (si estás en un entorno que no admite `prompt`, puedes simularlo con un arreglo de intentos predefinidos).
   - Si el número ingresado es mayor que el `numeroSecreto`, imprime `"Muy alto"`.
   - Si es menor, imprime `"Muy bajo"`.
5. Cuando el usuario adivine correctamente, sal del bucle e imprime un mensaje como `"¡Felicidades! Adivinaste el número secreto"`.

## Ejemplo de Salida
```plaintext
Adivina el número (entre 1 y 100):
50
Muy alto
Adivina el número (entre 1 y 100):
25
Muy bajo
Adivina el número (entre 1 y 100):
37
¡Felicidades! Adivinaste el número secreto
