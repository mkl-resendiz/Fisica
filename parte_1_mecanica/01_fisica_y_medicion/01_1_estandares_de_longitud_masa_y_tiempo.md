# 1.1 Estandares de longitud, masa y tiempo

## Resumen

La fisica describe fenomenos naturales mediante mediciones y relaciones matematicas entre cantidades fisicas. En mecanica, las tres cantidades fundamentales son **longitud, masa y tiempo**.

Para que una medicion pueda reproducirse, debe existir un estandar que sea accesible, confiable y estable. El Sistema Internacional (SI) utiliza como unidades fundamentales:

- longitud: metro (m);
- masa: kilogramo (kg);
- tiempo: segundo (s).

El metro actualmente se define a partir de la distancia que recorre la luz en el vacio durante un intervalo de tiempo exacto. El segundo se define mediante la frecuencia de la radiacion asociada al cesio-133.

El capitulo tambien distingue entre **tiempo**, que identifica un instante respecto a una referencia, e **intervalo de tiempo**, que representa una duracion.

Las cantidades como area, volumen, rapidez y densidad son cantidades derivadas. La densidad se define como:

$$
\\rho = \\frac{m}{V}
$$

donde $m$ es la masa y $V$ el volumen.

## Conceptos clave

- **Cantidad fisica:** propiedad que puede medirse.
- **Estandar:** referencia utilizada para comparar mediciones.
- **Cantidad fundamental:** no se expresa, dentro del sistema considerado, mediante otras cantidades mas basicas.
- **Cantidad derivada:** se obtiene combinando matematicamente cantidades fundamentales.
- **SI:** Sistema Internacional de Unidades.
- **Tiempo vs. intervalo de tiempo:** un instante no es lo mismo que una duracion.
- **Densidad:** masa por unidad de volumen.

## Formulas importantes

### Densidad

$$
\\rho = \\frac{m}{V}
$$

Se utiliza cuando se conocen la masa y el volumen de una sustancia y se desea saber cuanta masa corresponde a cada unidad de volumen.

Unidades SI:

$$
[\\rho] = \\frac{kg}{m^3}
$$

### Volumen de una esfera

Para una esfera de radio $r$:

$$
V = \\frac{4}{3}\\pi r^3
$$

Es util cuando el objeto puede modelarse como una esfera.

## Ejemplo del libro

### Problema

El libro propone calcular la densidad de un proton modelado como una esfera, utilizando su diametro y su masa.

### Datos

- Diametro del proton: $2.4\\,fm$.
- Masa: $1.67\\times10^{-27}\\,kg$.
- $1\\,fm=10^{-15}\\,m$.

El radio es:

$$
r = \\frac{2.4\\,fm}{2}=1.2\\times10^{-15}\\,m
$$

### Que se busca

La densidad del proton.

### Principio fisico

La densidad es masa dividida entre volumen. Como el proton se representa como una esfera, primero calculamos su volumen.

### Desarrollo paso a paso

$$
V=\\frac{4}{3}\\pi r^3
$$

Sustituyendo:

$$
V=\\frac{4}{3}\\pi(1.2\\times10^{-15}\\,m)^3
$$

$$
V\\approx7.24\\times10^{-45}\\,m^3
$$

Ahora usamos:

$$
\\rho=\\frac{m}{V}
$$

$$
\\rho=\\frac{1.67\\times10^{-27}\\,kg}
{7.24\\times10^{-45}\\,m^3}
$$

### Resultado

$$
\\boxed{\\rho\\approx2.31\\times10^{17}\\,kg/m^3}
$$

### Interpretacion fisica

La densidad resultante es enorme comparada con la de los materiales cotidianos. El ejercicio muestra como una medicion de masa y una escala geometrica extremadamente pequena pueden producir una densidad gigantesca.

## Ejercicios del final

### Ejercicio 1

Calcular la densidad promedio de la Tierra a partir de su masa y radio.

**Datos aproximados utilizados por el libro:**

$$
M=5.98\\times10^{24}\\,kg
$$

$$
R\\approx6.37\\times10^6\\,m
$$

**Solucion**

Modelamos la Tierra como esfera:

$$
V=\\frac{4}{3}\\pi R^3
$$

Entonces:

$$
\\rho=\\frac{M}{V}
=\\frac{3M}{4\\pi R^3}
$$

Sustituyendo:

$$
\\rho\\approx5.5\\times10^3\\,kg/m^3
$$

**Resultado:**

$$
\\boxed{\\rho\\approx5.5\\times10^3\\,kg/m^3}
$$

### Ejercicio 3

Dos esferas se cortan de la misma roca uniforme. Una tiene radio $4.50\\,cm$ y la otra tiene una masa cinco veces mayor. Encontrar el radio de la segunda.

**Principio fisico**

Como la roca es la misma, la densidad es constante:

$$
m=\\rho V=\\rho\\frac{4}{3}\\pi r^3
$$

Por tanto:

$$
m\\propto r^3
$$

Si $m_2=5m_1$:

$$
\\frac{m_2}{m_1}=\\left(\\frac{r_2}{r_1}\\right)^3=5
$$

Despejamos:

$$
r_2=r_1\\sqrt[3]{5}
$$

$$
r_2=(4.50\\,cm)\\sqrt[3]{5}
$$

$$
\\boxed{r_2\\approx7.69\\,cm}
$$

**Interpretacion:** multiplicar la masa por cinco no multiplica el radio por cinco porque la masa depende del volumen, y el volumen depende de $r^3$.

### Ejercicio 5

Evaluar si una persona situada a $200\\,km$ de altura podria distinguir una pared de $7\\,m$ de ancho con una agudeza visual de $3\\times10^{-4}\\,rad$.

El angulo subtendido es aproximadamente:

$$
\\theta\\approx\\frac{w}{d}
$$

Con:

$$
w=7\\,m,\\qquad d=200\\,000\\,m
$$

$$
\\theta\\approx\\frac{7}{200000}
=3.5\\times10^{-5}\\,rad
$$

La agudeza visual indicada es:

$$
3\\times10^{-4}\\,rad
$$

Como:

$$
3.5\\times10^{-5}<3\\times10^{-4}
$$

el angulo subtendido es menor que el minimo resoluble indicado.

**Resultado:** el objeto no seria distinguible bajo esas condiciones ideales.

## Dato curioso

El metro ha cambiado de definicion a medida que la ciencia necesitaba mayor precision. El libro contrasta las antiguas referencias materiales con la definicion basada en la velocidad de la luz.

## Ideas para recordar

- En mecanica, longitud, masa y tiempo son las cantidades fundamentales.
- El SI usa m, kg y s.
- Una unidad no es lo mismo que la cantidad fisica.
- La densidad relaciona masa y volumen.
- Siempre comprueba si el resultado tiene un orden de magnitud razonable.
