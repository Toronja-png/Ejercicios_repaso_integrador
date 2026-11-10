# Ejercicio 9: Listas — modificar y transformar

### Consigna

Crear un archivo `ej9.py` que trabaje sobre listas.

### Parte 1: Lista de palabras

1. Pedir al usuario palabras **indefinidamente**, hasta que escriba `fin`. Guardarlas en la lista `palabras`.
2. Mostrar cuántas palabras se ingresaron en total.
3. Mostrar cuántas palabras **distintas** hay (sin repetir).
4. Mostrar la **palabra más larga** y la más corta.

### Parte 2: Transformaciones

5. **Eliminar duplicados** de la lista `palabras`, manteniendo el orden en que aparecieron por primera vez.
   El resultado debe quedar en una lista nueva.
6. **Invertir** la lista de palabras y mostrarla.
7. Filtrar: de una lista de números cargada por el usuario, generar una **lista nueva solo con los pares**
   y otra **solo con los impares**, y mostrar las tres listas.

### Ejemplo de ejecución (fragmento)

```
Total de palabras: 5
Palabras distintas: 4
Palabra más larga: programacion
Palabra más corta: de

Lista original: ['hola', 'mundo', 'hola', 'programacion', 'hola']
Lista sin duplicados: ['hola', 'mundo', 'programacion']
Lista invertida: ['hola', 'programacion', 'hola', 'mundo', 'hola']
```

### Pistas

- Para saber si una palabra ya fue vista, se puede recorrer una lista auxiliar y comparar con `in`.
- Para agregar elementos a una lista nueva se usa `append`.
- El `while` con una condición `while palabra != "fin":` es la forma natural de cargar una cantidad indefinida
  de elementos.

### Desafío extra

Pedir al usuario una lista de números y mostrar, **sin usar `sorted()`**, cuál es el número más grande,
el más chico y cuál es el segundo más grande. (Pista: se puede rastrear el máximo dentro de un recorrido.)
