# 1.3 Analisis dimensional

## Resumen

El analisis dimensional permite comprobar si una ecuacion puede ser fisicamente correcta. La idea central es que ambos lados de una ecuacion deben tener las mismas dimensiones.

El libro usa:

- $L$ para longitud;
- $M$ para masa;
- $T$ para tiempo.

Las dimensiones no son lo mismo que las unidades. Por ejemplo, metros y pies son unidades diferentes, pero ambas representan la dimension longitud.

El analisis dimensional tambien permite deducir la forma de una relacion entre cantidades, aunque no determina por si solo constantes numericas adimensionales.

## Conceptos clave

- Dimension.
- Unidad.
- Homogeneidad dimensional.
- Cantidad fundamental.
- Cantidad derivada.
- Constante adimensional.
- Verificacion dimensional.
- Ley de potencias.

## Formulas importantes

Algunas dimensiones utiles:

$$
[v]=\\frac{L}{T}
$$

$$
[a]=\\frac{L}{T^2}
$$

$$
[A]=L^2
$$

$$
[V]=L^3
$$

Para comprobar una ecuacion, las dimensiones del lado izquierdo deben coincidir con las del lado derecho.

## Ejemplo del libro

### Problema

Comprobar que:

$$
v=at
$$

es dimensionalmente correcta.

### Datos

Rapidez:

$$
[v]=\\frac{L}{T}
$$

Aceleracion:

$$
[a]=\\frac{L}{T^2}
$$

Tiempo:

$$
[t]=T
$$

### Que se busca

Comprobar la consistencia dimensional.

### Principio fisico

Una ecuacion fisica debe ser dimensionalmente homogenea.

### Desarrollo paso a paso

En el lado derecho:

$$
[at]=\\frac{L}{T^2}(T)
$$

Por tanto:

$$
[at]=\\frac{L}{T}
$$

Esto coincide con:

$$
[v]=\\frac{L}{T}
$$

### Resultado

$$
\\boxed{v=at\\text{ es dimensionalmente correcta}}
$$

### Interpretacion fisica

La comprobacion no demuestra que la ecuacion describa completamente el fenomeno, pero si elimina ecuaciones que no pueden ser correctas.

## Ejercicios del final

### Ejercicio 8

Se propone:

$$
x=ka^m t^n
$$

donde $k$ es adimensional. Encontrar $m$ y $n$ mediante analisis dimensional.

Como $x$ tiene dimension $L$:

$$
L=[a]^m[t]^n
$$

$$
L=\\left(\\frac{L}{T^2}\\right)^mT^n
$$

$$
L=L^mT^{n-2m}
$$

Igualando exponentes:

$$
m=1
$$

$$
n-2m=0
$$

Entonces:

$$
n=2
$$

**Resultado:**

$$
\\boxed{x\\propto at^2}
$$

El analisis dimensional no determina el valor de $k$.

### Ejercicio 9

Determinar cuales de las ecuaciones propuestas son dimensionalmente correctas.

**a)**

$$
v_f=v_i+ax
$$

Los dos primeros terminos tienen dimension:

$$
\\frac{L}{T}
$$

pero:

$$
[ax]=\\frac{L}{T^2}L=\\frac{L^2}{T^2}
$$

No coinciden.

$$
\\boxed{\\text{a) Incorrecta}}
$$

**b)**

$$
y=(2\\,m)\\cos(kx)
$$

Para que el coseno sea valido, $kx$ debe ser adimensional. Como $k$ tiene unidades de $m^{-1}$ y $x$ de $m$:

$$
[kx]=1
$$

Ademas, $(2\\,m)$ tiene dimension $L$, igual que $y$.

$$
\\boxed{\\text{b) Correcta}}
$$

### Ejercicio 10

Para:

$$
x=At^3+Bt
$$

determinar las dimensiones de $A$, $B$ y de $dx/dt$.

Cada termino debe tener dimension $L$.

Para $At^3$:

$$
[A]T^3=L
$$

$$
\\boxed{[A]=\\frac{L}{T^3}}
$$

Para $Bt$:

$$
[B]T=L
$$

$$
\\boxed{[B]=\\frac{L}{T}}
$$

Ahora:

$$
\\frac{dx}{dt}=3At^2+B
$$

Cada termino tiene:

$$
\\frac{L}{T}
$$

Por tanto:

$$
\\boxed{\\left[\\frac{dx}{dt}\\right]=\\frac{L}{T}}
$$

## Dato curioso

El analisis dimensional puede descubrir la forma de una relacion sin conocer todos los detalles del fenomeno. Sin embargo, no puede determinar constantes numericas adimensionales como el $k$ de una expresion proporcional.

## Ideas para recordar

- Dimension no es lo mismo que unidad.
- Los dos lados de una ecuacion deben tener las mismas dimensiones.
- Los argumentos de funciones como seno, coseno y exponencial deben ser adimensionales.
- El analisis dimensional comprueba y restringe ecuaciones, pero no siempre determina constantes numericas.
