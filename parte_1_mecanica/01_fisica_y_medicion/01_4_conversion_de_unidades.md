# 1.4 Conversion de unidades

## Resumen

Las unidades se pueden tratar algebraicamente. Para convertir una cantidad, se multiplica por factores de conversion que equivalen a uno y se escoge su orientacion para que la unidad original se cancele.

El libro recomienda mantener las unidades durante todos los pasos del calculo. Esto permite detectar errores cuando las unidades finales no corresponden con la cantidad buscada.

Algunas equivalencias usadas en el capitulo:

$$
1\\,mi=1609\\,m=1.609\\,km
$$

$$
1\\,ft=0.3048\\,m
$$

$$
1\\,in.=0.0254\\,m
$$

## Conceptos clave

- Factor de conversion.
- Cancelacion algebraica de unidades.
- Unidades SI.
- Unidades del sistema usual U.S.
- Densidad y conversion de unidades.
- Mantener unidades durante todo el calculo.

## Formulas importantes

### Factor de conversion

Si:

$$
1\\,in.=2.54\\,cm
$$

entonces:

$$
\\frac{2.54\\,cm}{1\\,in.}=1
$$

Esto permite convertir:

$$
15.0\\,in.\\left(\\frac{2.54\\,cm}{1\\,in.}\\right)
$$

y cancelar pulgadas.

### Densidad

$$
\\rho=\\frac{m}{V}
$$

## Ejemplo del libro

### Problema

Un automovil viaja a $38.0\\,m/s$. Determinar si supera un limite de $75.0\\,mi/h$.

### Datos

$$
v=38.0\\,m/s
$$

$$
v_{lim}=75.0\\,mi/h
$$

### Que se busca

Expresar $38.0\\,m/s$ en $mi/h$.

### Principio fisico

Se usan factores de conversion que equivalen a uno, escogiendo su orientacion para cancelar unidades.

### Desarrollo paso a paso

Primero metros a millas:

$$
38.0\\frac{m}{s}
\\left(\\frac{1\\,mi}{1609\\,m}\\right)
$$

Despues segundos a horas:

$$
38.0\\frac{m}{s}
\\left(\\frac{1\\,mi}{1609\\,m}\\right)
\\left(\\frac{60\\,s}{1\\,min}\\right)
\\left(\\frac{60\\,min}{1\\,h}\\right)
$$

Resultado:

$$
v\\approx85.0\\,mi/h
$$

### Resultado

$$
\\boxed{38.0\\,m/s\\approx85.0\\,mi/h}
$$

Por tanto, la rapidez convertida es mayor que $75.0\\,mi/h$.

### Interpretacion fisica

La conversion no cambia la rapidez. Solo cambia la forma de expresarla.

## Ejercicios del final

### Ejercicio 11

Una pieza de plomo tiene masa $23.94\\,g$ y volumen $2.10\\,cm^3$. Calcular su densidad en unidades SI.

Primero:

$$
\\rho=\\frac{23.94\\,g}{2.10\\,cm^3}
=11.4\\,g/cm^3
$$

Como:

$$
1\\,g=10^{-3}\\,kg
$$

y:

$$
1\\,cm^3=10^{-6}\\,m^3
$$

entonces:

$$
1\\,g/cm^3=10^3\\,kg/m^3
$$

Por tanto:

$$
\\boxed{\\rho=1.14\\times10^4\\,kg/m^3}
$$

### Ejercicio 13

Encontrar el radio de una esfera de aluminio que equilibra una esfera de hierro de radio $2.00\\,cm$.

Densidades:

$$
\\rho_{Al}=2.70\\times10^3\\,kg/m^3
$$

$$
\\rho_{Fe}=7.86\\times10^3\\,kg/m^3
$$

En equilibrio, las masas son iguales:

$$
\\rho_{Al}\\frac{4}{3}\\pi r_{Al}^3
=
\\rho_{Fe}\\frac{4}{3}\\pi r_{Fe}^3
$$

Se simplifica:

$$
r_{Al}=r_{Fe}
\\left(\\frac{\\rho_{Fe}}{\\rho_{Al}}\\right)^{1/3}
$$

Sustituyendo:

$$
r_{Al}
=(2.00\\,cm)
\\left(\\frac{7.86}{2.70}\\right)^{1/3}
$$

$$
\\boxed{r_{Al}\\approx2.86\\,cm}
$$

### Ejercicio 15

Un galon de pintura tiene volumen $3.78\\times10^{-3}\\,m^3$ y cubre $25.0\\,m^2$. Encontrar el grosor.

El volumen de una capa uniforme es:

$$
V=At
$$

Despejamos:

$$
t=\\frac{V}{A}
$$

$$
t=\\frac{3.78\\times10^{-3}\\,m^3}{25.0\\,m^2}
$$

$$
\\boxed{t=1.51\\times10^{-4}\\,m}
$$

Equivale aproximadamente a:

$$
\\boxed{t=0.151\\,mm}
$$

## Dato curioso

El factor de conversion es una cantidad adimensional: representa una igualdad entre dos maneras de expresar la misma magnitud. Por eso puede multiplicarse por una cantidad sin cambiar su valor fisico.

## Ideas para recordar

- Una conversion correcta debe cancelar la unidad que no quieres.
- Nunca quites las unidades demasiado pronto.
- La unidad final debe corresponder con lo que se pregunta.
- Una conversion cambia la representacion numerica, no la cantidad fisica.
