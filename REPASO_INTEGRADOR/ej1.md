# Ejercicio 1: Presentación y datos personales

### Consigna

Crear un archivo `ej1.py` que le pida al usuario los siguientes datos:

- Nombre
- Apellido
- Año de nacimiento
- Ciudad

Luego debe mostrar un cartel con esos datos y la **edad** calculada del usuario (considerando que el año en curso
es 2026).

### Ejemplo de ejecución

```
Ingrese su nombre: Juan
Ingrese su apellido: Perez
Ingrese su año de nacimiento: 2008
Ingrese su ciudad: Mendoza

--- DATOS DEL USUARIO ---
Nombre completo: Juan Perez
Ciudad: Mendoza
Año de nacimiento: 2008
Edad: 18
```

### Pistas

- Todo lo que se lee con `input()` es **texto** (string), por más que el usuario escriba un número.
  Para poder operarlo hay que convertirlo: `int(...)` para enteros y `float(...)` para decimales.
- Las comillas simples y dobles son equivalentes en Python: `'texto'` o `"texto"`.
- Para concatenar texto se puede usar el `+`, pero lo más cómodo en Python son las *f-strings*:
  `f"Hola {nombre}, tenés {edad} años"`.

### Para pensar

¿Qué pasaría si el usuario escribiera `ocho` en lugar de `2008`? El programa se rompería, porque `int("ocho")`
no es un número válido. ¿Cómo se puede hacer para que el programa avise y vuelva a pedir el dato en lugar de
fallar? (Investigue por su cuenta el bloque `try` / `except`.)
