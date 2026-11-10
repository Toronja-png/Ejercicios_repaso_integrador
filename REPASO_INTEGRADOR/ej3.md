# Ejercicio 3: Clasificador de triángulos

### Consigna

Crear un archivo `ej3.py` que pida al usuario las longitudes de los tres lados de un triángulo y determine:

1. Si esas longitudes **pueden formar un triángulo**. Para que sí formen, la suma de dos lados debe ser
   **mayor** que el tercer lado (esto hay que comprobarlo para las tres combinaciones).
2. Si el triángulo es **equilátero** (los tres lados iguales), **isósceles** (dos lados iguales) o **escaleno**
   (todos distintos).
3. Si el triángulo es **rectángulo**, usando el teorema de Pitágoras: `a**2 + b**2 == c**2`.

### Ejemplo de ejecución

```
Ingrese el lado A: 3
Ingrese el lado B: 4
Ingrese el lado C: 5

Es un triángulo válido.
Tipo: escaleno.
¿Rectángulo?: Si
```

### Pistas

- Usá `if` / `elif` / `else`. El orden de las condiciones importa: primero validá que sea un triángulo,
  después clasificá.
- Para que sea rectángulo, el lado mayor es necesariamente la hipotenusa. Podés ordenar los tres lados
  para que el mayor quede en una variable conocida.

### Para pensar

Si los lados fueran `2`, `2` y `4`, ¿el programa debería decir que es isósceles? ¿Por qué? ¿En qué orden
evaluaste las condiciones y por qué ese orden es el correcto?
