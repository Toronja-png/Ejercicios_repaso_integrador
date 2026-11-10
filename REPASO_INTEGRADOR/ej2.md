# Ejercicio 2: Operaciones con variables e intercambio de valores

### Consigna

Crear un archivo `ej2.py` que:

1. Pida al usuario dos números enteros (`a` y `b`).
2. Muestre la **suma**, la **resta**, el **producto**, el **cociente** y el **resto** de dividir `a` por `b`.
3. **Intercambie** los valores de `a` y `b` *sin usar una variable auxiliar* y los muestre.
4. Muestre el promedio de los dos números con dos decimales.

### Ejemplo de ejecución

```
Ingrese el primer número (a): 10
Ingrese el segundo número (b): 4

Suma: 14
Resta: 6
Producto: 40
Cociente: 2.5
Resto: 0

Valores intercambiados:
a = 4
b = 10

Promedio: 7.0
```

### Pistas

- En Python se pueden asignar varias variables en una sola línea: `a, b = b, a`.
- La división con `/` siempre devuelve un `float`. La división entera se hace con `//`.
- `round(numero, 2)` redondea a dos decimales.

### Para pensar

¿Qué diferencia hay entre `10 / 2` y `10 // 2`? ¿Y entre `10 / 4` y `10 // 4`? Anotá la respuesta y el tipo de
dato (`type`) de cada resultado.
