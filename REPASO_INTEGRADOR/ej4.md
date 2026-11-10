# Ejercicio 4: Menú de calculadora con validaciones

### Consigna

Crear un archivo `ej4.py` que simule una calculadora mediante un **menú**. En este ejercicio todavía no hace
falta usar bucles: se pide **una sola vez** la opción y se resuelve.

El menú debe ser:

```
1. Suma
2. Resta
3. Multiplicación
4. División
5. Promedio de dos números
```

El programa debe:

1. Mostrar el menú.
2. Pedir la opción.
3. Si la opción es válida, pedir los dos números y mostrar el resultado.
4. Si la opción **no es válida**, mostrar un mensaje de error (por ejemplo: *"Opción no válida"*).
5. En el caso de la **división**, tener en cuenta que no se puede dividir por cero: si el segundo número es `0`,
   avisar que la operación no es posible.
6. En el caso del **promedio**, mostrar el resultado con dos decimales.

### Ejemplo de ejecución

```
1. Suma
2. Resta
3. Multiplicación
4. División
5. Promedio de dos números

Ingrese una opción: 4
Ingrese el primer número: 10
Ingrese el segundo número: 0

No se puede dividir por cero.
```

### Pistas

- La estructura general es: `if` para una opción, `elif` para las otras, y `else` para el error.
- La condición para la división por cero es `if segundo == 0:`.
- Cuidado con la indentación: en Python los bloques se delimitan con espacios (recomendado: 4 espacios).

### Para pensar

¿Qué pasaría si el usuario escribiera `"4"` (con comillas) o `4.5`? ¿Cómo adentro del `if` se puede
asegurarse de que la opción sea un número entre 1 y 5? (Pista: existen los operadores `and` y `or`.)
