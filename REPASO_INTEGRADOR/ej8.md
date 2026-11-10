# Ejercicio 8: Listas — carga, recorrido y cálculos

### Consigna

Crear un archivo `ej8.py` que trabaje con una lista de notas.

1. Pedir al usuario **5 notas** (decimales) y guardarlas en una lista llamada `notas`.
2. Mostrar la lista completa.
3. Mostrar el **promedio** de las notas (con dos decimales).
4. Mostrar la **nota más alta** y la **nota más baja**.
5. Mostrar cuántas notas están **aprobadas** (mayor o igual a 6) y cuántas reprobadas.
6. Mostrar la lista en **orden inverso**, sin usar el método `reverse()`.
7. Pedir al usuario una nota e informar **en qué posición (índice) está** dentro de la lista. Si la nota no
   está en la lista, avisar que no aparece.

### Ejemplo de ejecución (fragmento)

```
Las notas son: [8.5, 4.0, 9.0, 6.5, 7.0]
Promedio: 7.0
Nota más alta: 9.0
Nota más baja: 4.0
Cantidad de aprobadas: 4
Cantidad de reprobadas: 1
Lista invertida: [7.0, 6.5, 9.0, 4.0, 8.5]
```

### Pistas

- Para cargar la lista: `notas = []` y después `notas.append(nota)` dentro de un `for`.
- Para el promedio se puede usar `sum(notas)` y `len(notas)`.
- `max(lista)` y `min(lista)` dan el máximo y el mínimo.
- Para invertir una lista **sin** `reverse()` se puede recorrer al revés: `for i in range(len(lista) - 1, -1, -1):`.
- Para buscar un elemento: `if nota in notas:` y, si se quiere saber la posición, `lista.index(elemento)`.

### Para pensar

¿Qué pasa si el usuario carga dos notas iguales? ¿`index()` devuelve la primera o la última posición?
¿Qué habría que cambiar para que el programa acepte cualquier cantidad de notas y no solamente 5?
