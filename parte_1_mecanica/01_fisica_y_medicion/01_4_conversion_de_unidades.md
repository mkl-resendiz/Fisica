# 1.4 Conversion de unidades

## Resumen

Las unidades se manipulan algebraicamente. Un factor de conversion es una fraccion cuyo valor es uno, pero permite cambiar la unidad.

Por ejemplo:

$$
1\,in.=2.54\,cm
$$

entonces:

$$
\frac{2.54\,cm}{1\,in.}=1
$$

La orientacion correcta del factor se elige para cancelar la unidad original.

## Conceptos clave

- Factor de conversion.
- Cancelacion de unidades.
- SI.
- Conversion entre sistemas.
- Conversion encadenada.

## Formulas importantes

Si:

$$
1\,mi=1609\,m
$$

entonces:

$$
\frac{1\,mi}{1609\,m}=1
$$

y tambien:

$$
\frac{1609\,m}{1\,mi}=1
$$

Ambos factores valen uno; se elige el que produzca la cancelacion deseada.

## Ejemplo del libro

### Problema

Un automovil viaja a $38.0\,m/s$. Determinar si supera un limite de $75.0\,mi/h$.

### Datos

$$
v=38.0\,m/s
$$

$$
v_{lim}=75.0\,mi/h
$$

### Que se busca

Convertir $38.0\,m/s$ a $mi/h$.

### Principio fisico

Usar factores de conversion sin perder unidades.

### Desarrollo paso a paso

Primero convertimos metros a millas:

$$
38.0\frac{m}{s}
\left(\frac{1\,mi}{1609\,m}\right)
$$

Se cancela $m$:

$$
=
\frac{38.0}{1609}\frac{mi}{s}
$$

Ahora convertimos segundos a minutos:

$$
\frac{38.0}{1609}\frac{mi}{s}
\left(\frac{60\,s}{1\,min}\right)
$$

Se cancela $s$.

Finalmente convertimos minutos a horas:

$$
\frac{38.0}{1609}\frac{mi}{s}
\left(\frac{60\,s}{1\,min}\right)
\left(\frac{60\,min}{1\,h}\right)
$$

Se cancelan $s$ y $min$:

$$
v=
38.0
\left(\frac{1}{1609}\right)
(60)(60)
\frac{mi}{h}
$$

$$
v\approx85.0\,mi/h
$$

### Resultado

$$
\boxed{38.0\,m/s\approx85.0\,mi/h}
$$

Como $85.0>75.0$:

$$
\boxed{\text{la rapidez supera el limite indicado}}
$$

### Interpretacion fisica

La rapidez no cambio; solamente cambio su unidad.

## Ejercicios del final

### Ejercicio 11 — Densidad del plomo en SI

Datos:

$$
m=23.94\,g
$$

$$
V=2.10\,cm^3
$$

Primero:

$$
\rho=\frac{m}{V}
$$

$$
\rho=
\frac{23.94\,g}{2.10\,cm^3}
$$

$$
\rho=11.4\,g/cm^3
$$

Ahora convertimos:

$$
1\,g=10^{-3}\,kg
$$

$$
1\,cm=10^{-2}\,m
$$

Como el volumen esta al cubo:

$$
1\,cm^3=(10^{-2}\,m)^3
$$

$$
1\,cm^3=10^{-6}\,m^3
$$

Entonces:

$$
1\,\frac{g}{cm^3}
=
\frac{10^{-3}\,kg}{10^{-6}\,m^3}
$$

$$
1\,\frac{g}{cm^3}
=
10^3\,\frac{kg}{m^3}
$$

Por tanto:

$$
\rho=
(11.4\,g/cm^3)
\left(
10^3\,\frac{kg/m^3}{g/cm^3}
\right)
$$

$$
\boxed{\rho=1.14\times10^4\,kg/m^3}
$$

### Ejercicio 13 — Esfera de aluminio

Datos:

$$
V=1.00\,m^3
$$

$$
m_{Al}=2.70\times10^3\,kg
$$

$$
m_{Fe}=7.86\times10^3\,kg
$$

$$
r_{Fe}=2.00\,cm
$$

Densidades:

$$
\rho_{Al}=2.70\times10^3\,kg/m^3
$$

$$
\rho_{Fe}=7.86\times10^3\,kg/m^3
$$

En equilibrio, las masas son iguales:

$$
m_{Al}=m_{Fe}
$$

Como:

$$
m=\rho V
$$

entonces:

$$
\rho_{Al}V_{Al}
=
\rho_{Fe}V_{Fe}
$$

Para esferas:

$$
\rho_{Al}\frac{4}{3}\pi r_{Al}^3
=
\rho_{Fe}\frac{4}{3}\pi r_{Fe}^3
$$

Cancelamos $4/3$ y $\pi$:

$$
\rho_{Al}r_{Al}^3
=
\rho_{Fe}r_{Fe}^3
$$

Despejamos:

$$
r_{Al}^3
=
\frac{\rho_{Fe}}{\rho_{Al}}r_{Fe}^3
$$

Aplicamos raiz cubica:

$$
r_{Al}
=
r_{Fe}
\left(\frac{\rho_{Fe}}{\rho_{Al}}\right)^{1/3}
$$

Sustituimos:

$$
r_{Al}
=
(2.00\,cm)
\left(
\frac{7.86\times10^3}
{2.70\times10^3}
\right)^{1/3}
$$

Se cancelan $10^3$:

$$
r_{Al}
=
(2.00\,cm)
\left(
\frac{7.86}{2.70}
\right)^{1/3}
$$

$$
\boxed{r_{Al}\approx2.86\,cm}
$$

### Ejercicio 15 — Grosor de pintura

Datos:

$$
V=3.78\times10^{-3}\,m^3
$$

$$
A=25.0\,m^2
$$

Para una capa uniforme:

$$
V=At
$$

Despejamos:

$$
t=\frac{V}{A}
$$

Sustituimos:

$$
t=
\frac{3.78\times10^{-3}\,m^3}
{25.0\,m^2}
$$

Se simplifican las unidades:

$$
\frac{m^3}{m^2}=m
$$

Entonces:

$$
t=
\frac{3.78\times10^{-3}}{25.0}\,m
$$

$$
\boxed{t=1.51\times10^{-4}\,m}
$$

En milimetros:

$$
1\,m=1000\,mm
$$

$$
t=(1.51\times10^{-4}\,m)(1000\,mm/m)
$$

$$
\boxed{t=0.151\,mm}
$$

## Dato curioso

Un factor de conversion no altera la cantidad fisica porque su valor es exactamente uno; solamente cambia la forma en que expresamos esa cantidad.

## Ideas para recordar

- Decide primero que unidad quieres al final.
- Coloca el factor para que la unidad original se cancele.
- Lleva las unidades en todos los pasos.
- Si una unidad esta elevada a una potencia, el factor de conversion tambien debe elevarse.
