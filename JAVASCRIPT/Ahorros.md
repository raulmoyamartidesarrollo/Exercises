# Ejercicio: Contador de Ahorros

## Descripción
Crea un programa en JavaScript que simule un contador de ahorros. El usuario puede ingresar diferentes montos para sumar a su cuenta de ahorros hasta que decida detenerse. Utiliza un bucle `while` para mantener el programa en ejecución hasta que el usuario escriba `"salir"`.

## Instrucciones
1. Crea una variable llamada `ahorros` e inicialízala con `0`.
2. Usa un bucle `while` que se ejecute indefinidamente.
3. Dentro del bucle:
   - Solicita al usuario que ingrese un monto a través de `prompt()` (o simula entradas si `prompt` no está disponible).
   - Si el usuario escribe `"salir"`, termina el bucle.
   - Convierte la entrada a un número y súmala a la variable `ahorros`.
   - Muestra el monto actual de los ahorros.
4. Al finalizar el bucle, muestra un mensaje con el total de los ahorros.

## Ejemplo de Salida
```plaintext
Ingresa un monto para ahorrar: 100
Tus ahorros actuales son: 100

Ingresa un monto para ahorrar: 50
Tus ahorros actuales son: 150

Ingresa un monto para ahorrar: salir
Has terminado. Tus ahorros totales son: 150
