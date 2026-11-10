# Ejercicio 7: Bucles anidados

### Consigna

Crear un archivo `ej7.py` que use **bucles anidados** (un `for` dentro de otro `for`) para resolver:

1. **La tabla del 1 al 9.** Imprimir una tabla aritmética de 9 x 9, con el formato:
   ```
   1 x 1 = 1
   1 x 2 = 2
   ...
   1 x 9 = 9
   2 x 1 = 2
   2 x 2 = 4
   ...
   ```
2. **Triángulo de asteriscos.** Imprimir el siguiente triángulo:
   ```
   *
   **
   ***
   ****
   *****
   ```
3. **Triángulo invertido.** Imprimir el mismo triángulo, pero al revés:
   ```
   *****
   ****
   ***
   **
   *
   ```
4. **Tablero de ajedrez.** Imprimir un tablero de 8 filas y 8 columnas donde las posiciones pares
   (fila + columna par) lleven una `X` y las impares un `-`:
   ```
   X - X - X - X -
   - X - X - X - X
   X - X - X - X -
   ...
   ```

### Pistas

- El bucle externo maneja las **filas** y el interno las **columnas**.
- La condición para la posición par se puede escribir como `if (fila + columna) % 2 == 0:`.
- Para imprimir varios espacios o asteriscos seguidos se puede usar `"*" * cantidad` (el `*` de un string
  repite el texto).

### Para pensar

¿Cómo harías para imprimir un triángulo *centrado* (con los asteriscos alineados al centro) en lugar de
alineados a la izquierda? ¿Y para imprimir un rombo?
