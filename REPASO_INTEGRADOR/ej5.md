# Ejercicio 5: Bucles `for` y `range`

### Consigna

Crear un archivo `ej5.py` que, usando un `for` con `range`, resuelva lo siguiente:

1. **Suma de los números del 1 al N.** El usuario indica el valor de `N` y el programa muestra el resultado.
   (No usar la fórmula matemática: `N * (N + 1) / 2`. Hay que sumar en el camino.)
2. **Tabla de multiplicar del 7**, del 1 al 10, con el siguiente formato:
   ```
   7 x 1 = 7
   7 x 2 = 14
   7 x 3 = 21
   ```
   ...y así hasta el 10.
3. **Factorial de un número N** (recordá: `5! = 5 x 4 x 3 x 2 x 1`, y `0! = 1`).
4. **Números pares e impares** entre 1 y 100: mostrar cuántos pares hay, cuántos impares y cuáles son los pares.

### Ejemplo de ejecución (fragmento)

```
Ingrese un número N: 5
La suma de los números del 1 al 5 es: 15

7 x 1 = 7
7 x 2 = 14
...

El factorial de 5 es: 120

Cantidad de números pares entre 1 y 100: 50
Cantidad de números impares entre 1 y 100: 50
```

### Pistas

- `range(1, N + 1)` genera los números del 1 al N inclusive. `range(N)` va del 0 al N-1.
- `range(1, 101, 2)` genera los números impares: el tercer parámetro es el *paso*.
- Para concatenar texto y números dentro de un `print`, usá f-strings: `f"7 x {i} = {7 * i}"`.

### Para pensar

¿Qué pasaría si el factorial se calculara con `range(1, N)` en lugar de `range(1, N + 1)`? ¿Y si `N` fuera `0`?
Agregá una validación para que `N` no sea negativo.
