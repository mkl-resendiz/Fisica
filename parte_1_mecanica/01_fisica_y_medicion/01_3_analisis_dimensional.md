# 1.3 Analisis dimensional

## Resumen

El analisis dimensional trata las dimensiones como cantidades algebraicas. Una ecuacion fisica debe ser homogenea: los dos lados deben tener las mismas dimensiones.

En el libro:

<div align="center">

$[L]=L,\qquad[M]=M,\qquad[T]=T$

</div>

Algunas dimensiones utiles son:

<div align="center">

$[v]=\frac{L}{T}$

</div>

<div align="center">

$[a]=\frac{L}{T^2}$

</div>

<div align="center">

$[A]=L^2$

</div>

<div align="center">

$[V]=L^3$

</div>

El analisis dimensional puede comprobar ecuaciones y determinar exponentes en relaciones de proporcionalidad, pero no determina constantes numericas adimensionales.

## Conceptos clave

- Dimension.
- Unidad.
- Homogeneidad dimensional.
- Exponente dimensional.
- Constante adimensional.
- Ley de potencias.

## Formulas importantes

### Rapidez

<div align="center">

$[v]=\frac{L}{T}$

</div>

### Aceleracion

<div align="center">

$[a]=\frac{L}{T^2}$

</div>

### Posicion con aceleracion

La expresion:

<div align="center">

$x\propto at^2$

</div>

es dimensionalmente posible porque:

<div align="center">

$[a t^2] = \frac{L}{T^2}T^2 =L$

</div>

## Ejemplo del libro

### Problema

Demostrar que:

<div align="center">

$v=at$

</div>

es dimensionalmente correcta.

### Datos

<div align="center">

$[v]=\frac{L}{T}$

</div>

<div align="center">

$[a]=\frac{L}{T^2}$

</div>

<div align="center">

$[t]=T$

</div>

### Que se busca

Comprobar que ambos lados tienen la misma dimension.

### Principio fisico

Una ecuacion fisica debe ser dimensionalmente homogenea.

### Desarrollo paso a paso

Lado izquierdo:

<div align="center">

$[v]=\frac{L}{T}$

</div>

Lado derecho:

<div align="center">

$[at]=[a][t]$

</div>

Sustituimos:

<div align="center">

$[at]=\left(\frac{L}{T^2}\right)(T)$

</div>

Cancelamos un factor $T$:

<div align="center">

$[at]=\frac{L}{T}$

</div>

Por tanto:

<div align="center">

$[v]=[at]$

</div>

### Resultado

<div align="center">

$\boxed{v=at\text{ es dimensionalmente correcta}}$

</div>

### Interpretacion fisica

La prueba dimensional indica que la ecuacion tiene una forma compatible con las dimensiones, pero no demuestra por si sola que sea la ley fisica completa.

## Ejercicios del final

### Ejercicio 8

Se propone:

<div align="center">

$x=ka^m t^n$

</div>

donde $k$ es adimensional.

Como:

<div align="center">

$[x]=L$

</div>

y:

<div align="center">

$[a]=\frac{L}{T^2}$

</div>

entonces:

<div align="center">

$L= \left(\frac{L}{T^2}\right)^mT^n$

</div>

Aplicamos las potencias:

<div align="center">

$L=L^mT^{-2m+n}$

</div>

Para que ambos lados sean iguales:

<div align="center">

$m=1$

</div>

y:

<div align="center">

$-2m+n=0$

</div>

Sustituimos $m=1$:

<div align="center">

$-2(1)+n=0$

</div>

<div align="center">

$n=2$

</div>

Por tanto:

<div align="center">

$\boxed{x=kat^2}$

</div>

El analisis dimensional no permite obtener el valor numerico de $k$.

### Ejercicio 9

**a)**

<div align="center">

$v_f=v_i+ax$

</div>

Dimensiones de los primeros terminos:

<div align="center">

$[v_f]=[v_i]=\frac{L}{T}$

</div>

Pero:

<div align="center">

$[ax]= \left(\frac{L}{T^2}\right)(L) = \frac{L^2}{T^2}$

</div>

Como:

<div align="center">

$\frac{L}{T}\neq\frac{L^2}{T^2}$

</div>

la ecuacion es dimensionalmente incorrecta.

<div align="center">

$\boxed{\text{a) Incorrecta}}$

</div>

**b)**

<div align="center">

$y=(2\,m)\cos(kx)$

</div>

Para que el argumento del coseno sea valido:

<div align="center">

$[kx]=1$

</div>

El problema da:

<div align="center">

$[k]=m^{-1}$

</div>

y:

<div align="center">

$[x]=m$

</div>

Por tanto:

<div align="center">

$[kx]=(m^{-1})(m)=1$

</div>

Ademas, $2\,m$ tiene dimension de longitud, igual que $y$.

<div align="center">

$\boxed{\text{b) Correcta}}$

</div>

### Ejercicio 10

Dada:

<div align="center">

$x=At^3+Bt$

</div>

Cada termino debe tener dimension de longitud.

Para el primer termino:

<div align="center">

$[At^3]=L$

</div>

<div align="center">

$[A]T^3=L$

</div>

Despejamos:

<div align="center">

$\boxed{[A]=\frac{L}{T^3}}$

</div>

Para el segundo:

<div align="center">

$[Bt]=L$

</div>

<div align="center">

$[B]T=L$

</div>

<div align="center">

$\boxed{[B]=\frac{L}{T}}$

</div>

Ahora:

<div align="center">

$\frac{dx}{dt}=3At^2+B$

</div>

Como $dx/dt$ es rapidez:

<div align="center">

$\boxed{\left[\frac{dx}{dt}\right]=\frac{L}{T}}$

</div>

## Dato curioso

El analisis dimensional puede predecir la forma de una relacion, pero no necesariamente sus constantes numericas. En el ejemplo de movimiento circular, la constante adimensional solo puede determinarse con fisica adicional.

## Ideas para recordar

- Dimension y unidad no son lo mismo.
- No se pueden sumar cantidades con dimensiones diferentes.
- Los argumentos de seno, coseno y funciones similares deben ser adimensionales.
- El analisis dimensional es una prueba de consistencia, no una demostracion completa de una ley.
