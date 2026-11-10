# Ejercicio 6: Bucle `while` y validación de entrada

### Consigna

Crear un archivo `ej6.py` que use el bucle `while` para resolver dos situaciones distintas.

### Parte 1: Validación de un número

El programa debe pedir al usuario **un número entero positivo**. Si el usuario escribe algo que no sea un número,
o escribe un número menor o igual a cero, el programa debe **avisar y volver a pedir el dato** (sin romperse y sin
salir del programa). Cuando el dato sea correcto, se muestra un mensaje de confirmación.

```
Ingrese un número entero positivo: -3
El número debe ser positivo. Intente nuevamente.
Ingrese un número entero positivo: hola
Ingrese un número entero positivo: 12
El número ingresado es 12
```

### Parte 2: Acumulador hasta un centinela

El programa debe pedir números **indefinidamente** hasta que el usuario ingrese un `0`. Al terminar, debe mostrar:

- La cantidad de números ingresados (sin contar el cero).
- La suma de todos ellos.
- El promedio.
- El número mayor y el número menor.

```
Ingrese un número (0 para terminar): 8
Ingrese un número (0 para terminar): 3
Ingrese un número (0 para terminar): 0

Cantidad de números ingresados: 2
Suma: 11
Promedio: 5.5
Mayor: 8
Menor: 3
```

### Pistas

- Un `while` se repite **mientras la condición sea verdadera**. El `0` se usa como *centinela*: es la señal
  de que hay que terminar.
- Para validar que lo que se leyó es un número se puede usar el método `isdigit()` de los strings:
  `"12".isdigit()` devuelve `True`, `"hola".isdigit()` devuelve `False`.
- Cuidado con los bucles infinitos: asegurate de que la condición tenga alguna forma de volverse falsa.

### Desafío extra

Repetí la Parte 1 usando `try` / `except` en lugar de `isdigit()`, de modo que el programa también acepte
números negativos escritos con signo (por ejemplo `-3`) y los descarte.
