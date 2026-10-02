# 1.3 Analisis dimensional

## Resumen

El analisis dimensional trata las dimensiones como cantidades algebraicas. Una ecuacion fisica debe ser homogenea: los dos lados deben tener las mismas dimensiones.

En el libro:

$[L]=L,\qquad[M]=M,\qquad[T]=T$

Algunas dimensiones utiles son:

$[v]=\frac{L}{T}$

$[a]=\frac{L}{T^2}$

$[A]=L^2$

$[V]=L^3$

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

$[v]=\frac{L}{T}$

### Aceleracion

$[a]=\frac{L}{T^2}$

### Posicion con aceleracion

La expresion:

$x\propto at^2$

es dimensionalmente posible porque:

$[a t^2] = \frac{L}{T^2}T^2 =L$

## Ejemplo del libro

### Problema

Demostrar que:

$v=at$

es dimensionalmente correcta.

### Datos

$[v]=\frac{L}{T}$

$[a]=\frac{L}{T^2}$

$[t]=T$

### Que se busca

Comprobar que ambos lados tienen la misma dimension.

### Principio fisico

Una ecuacion fisica debe ser dimensionalmente homogenea.

### Desarrollo paso a paso

Lado izquierdo:

$[v]=\frac{L}{T}$

Lado derecho:

$[at]=[a][t]$

Sustituimos:

$[at]=\left(\frac{L}{T^2}\right)(T)$

Cancelamos un factor $T$:

$[at]=\frac{L}{T}$

Por tanto:

$[v]=[at]$

### Resultado

$\boxed{v=at\text{ es dimensionalmente correcta}}$

### Interpretacion fisica

La prueba dimensional indica que la ecuacion tiene una forma compatible con las dimensiones, pero no demuestra por si sola que sea la ley fisica completa.

## Ejercicios del final

### Ejercicio 8

Se propone:

$x=ka^m t^n$

donde $k$ es adimensional.

Como:

$[x]=L$

y:

$[a]=\frac{L}{T^2}$

entonces:

$L= \left(\frac{L}{T^2}\right)^mT^n$

Aplicamos las potencias:

$L=L^mT^{-2m+n}$

Para que ambos lados sean iguales:

$m=1$

y:

$-2m+n=0$

Sustituimos $m=1$:

$-2(1)+n=0$

$n=2$

Por tanto:

$\boxed{x=kat^2}$

El analisis dimensional no permite obtener el valor numerico de $k$.

### Ejercicio 9

**a)**

$v_f=v_i+ax$

Dimensiones de los primeros terminos:

$[v_f]=[v_i]=\frac{L}{T}$

Pero:

$[ax]= \left(\frac{L}{T^2}\right)(L) = \frac{L^2}{T^2}$

Como:

$\frac{L}{T}\neq\frac{L^2}{T^2}$

la ecuacion es dimensionalmente incorrecta.

$\boxed{\text{a) Incorrecta}}$

**b)**

$y=(2\,m)\cos(kx)$

Para que el argumento del coseno sea valido:

$[kx]=1$

El problema da:

$[k]=m^{-1}$

y:

$[x]=m$

Por tanto:

$[kx]=(m^{-1})(m)=1$

Ademas, $2\,m$ tiene dimension de longitud, igual que $y$.

$\boxed{\text{b) Correcta}}$

### Ejercicio 10

Dada:

$x=At^3+Bt$

Cada termino debe tener dimension de longitud.

Para el primer termino:

$[At^3]=L$

$[A]T^3=L$

Despejamos:

$\boxed{[A]=\frac{L}{T^3}}$

Para el segundo:

$[Bt]=L$

$[B]T=L$

$\boxed{[B]=\frac{L}{T}}$

Ahora:

$\frac{dx}{dt}=3At^2+B$

Como $dx/dt$ es rapidez:

$\boxed{\left[\frac{dx}{dt}\right]=\frac{L}{T}}$

## Dato curioso

El analisis dimensional puede predecir la forma de una relacion, pero no necesariamente sus constantes numericas. En el ejemplo de movimiento circular, la constante adimensional solo puede determinarse con fisica adicional.

## Ideas para recordar

- Dimension y unidad no son lo mismo.
- No se pueden sumar cantidades con dimensiones diferentes.
- Los argumentos de seno, coseno y funciones similares deben ser adimensionales.
- El analisis dimensional es una prueba de consistencia, no una demostracion completa de una ley.
