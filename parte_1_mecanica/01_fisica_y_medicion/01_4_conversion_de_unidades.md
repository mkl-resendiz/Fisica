# 1.4 Conversion de unidades

## Resumen

Las unidades se manipulan algebraicamente. Un factor de conversion es una fraccion cuyo valor es uno, pero permite cambiar la unidad.

Por ejemplo:

<div align="center">

$1\,in.=2.54\,cm$

</div>

entonces:

<div align="center">

$\frac{2.54\,cm}{1\,in.}=1$

</div>

La orientacion correcta del factor se elige para cancelar la unidad original.

## Conceptos clave

- Factor de conversion.
- Cancelacion de unidades.
- SI.
- Conversion entre sistemas.
- Conversion encadenada.

## Formulas importantes

Si:

<div align="center">

$1\,mi=1609\,m$

</div>

entonces:

<div align="center">

$\frac{1\,mi}{1609\,m}=1$

</div>

y tambien:

<div align="center">

$\frac{1609\,m}{1\,mi}=1$

</div>

Ambos factores valen uno; se elige el que produzca la cancelacion deseada.

## Ejemplo del libro

### Problema

Un automovil viaja a $38.0\,m/s$. Determinar si supera un limite de $75.0\,mi/h$.

### Datos

<div align="center">

$v=38.0\,m/s$

</div>

<div align="center">

$v_{lim}=75.0\,mi/h$

</div>

### Que se busca

Convertir $38.0\,m/s$ a $mi/h$.

### Principio fisico

Usar factores de conversion sin perder unidades.

### Desarrollo paso a paso

Primero convertimos metros a millas:

<div align="center">

$38.0\frac{m}{s} \left(\frac{1\,mi}{1609\,m}\right)$

</div>

Se cancela $m$:

<div align="center">

$= \frac{38.0}{1609}\frac{mi}{s}$

</div>

Ahora convertimos segundos a minutos:

<div align="center">

$\frac{38.0}{1609}\frac{mi}{s} \left(\frac{60\,s}{1\,min}\right)$

</div>

Se cancela $s$.

Finalmente convertimos minutos a horas:

<div align="center">

$\frac{38.0}{1609}\frac{mi}{s} \left(\frac{60\,s}{1\,min}\right) \left(\frac{60\,min}{1\,h}\right)$

</div>

Se cancelan $s$ y $min$:

<div align="center">

$v= 38.0 \left(\frac{1}{1609}\right) (60)(60) \frac{mi}{h}$

</div>

<div align="center">

$v\approx85.0\,mi/h$

</div>

### Resultado

<div align="center">

$\boxed{38.0\,m/s\approx85.0\,mi/h}$

</div>

Como $85.0>75.0$:

<div align="center">

$\boxed{\text{la rapidez supera el limite indicado}}$

</div>

### Interpretacion fisica

La rapidez no cambio; solamente cambio su unidad.

## Ejercicios del final

### Ejercicio 11 — Densidad del plomo en SI

Datos:

<div align="center">

$m=23.94\,g$

</div>

<div align="center">

$V=2.10\,cm^3$

</div>

Primero:

<div align="center">

$\rho=\frac{m}{V}$

</div>

<div align="center">

$\rho= \frac{23.94\,g}{2.10\,cm^3}$

</div>

<div align="center">

$\rho=11.4\,g/cm^3$

</div>

Ahora convertimos:

<div align="center">

$1\,g=10^{-3}\,kg$

</div>

<div align="center">

$1\,cm=10^{-2}\,m$

</div>

Como el volumen esta al cubo:

<div align="center">

$1\,cm^3=(10^{-2}\,m)^3$

</div>

<div align="center">

$1\,cm^3=10^{-6}\,m^3$

</div>

Entonces:

<div align="center">

$1\,\frac{g}{cm^3} = \frac{10^{-3}\,kg}{10^{-6}\,m^3}$

</div>

<div align="center">

$1\,\frac{g}{cm^3} = 10^3\,\frac{kg}{m^3}$

</div>

Por tanto:

<div align="center">

$\rho= (11.4\,g/cm^3) \left( 10^3\,\frac{kg/m^3}{g/cm^3} \right)$

</div>

<div align="center">

$\boxed{\rho=1.14\times10^4\,kg/m^3}$

</div>

### Ejercicio 13 — Esfera de aluminio

Datos:

<div align="center">

$V=1.00\,m^3$

</div>

<div align="center">

$m_{Al}=2.70\times10^3\,kg$

</div>

<div align="center">

$m_{Fe}=7.86\times10^3\,kg$

</div>

<div align="center">

$r_{Fe}=2.00\,cm$

</div>

Densidades:

<div align="center">

$\rho_{Al}=2.70\times10^3\,kg/m^3$

</div>

<div align="center">

$\rho_{Fe}=7.86\times10^3\,kg/m^3$

</div>

En equilibrio, las masas son iguales:

<div align="center">

$m_{Al}=m_{Fe}$

</div>

Como:

<div align="center">

$m=\rho V$

</div>

entonces:

<div align="center">

$\rho_{Al}V_{Al} = \rho_{Fe}V_{Fe}$

</div>

Para esferas:

<div align="center">

$\rho_{Al}\frac{4}{3}\pi r_{Al}^3 = \rho_{Fe}\frac{4}{3}\pi r_{Fe}^3$

</div>

Cancelamos $4/3$ y $\pi$:

<div align="center">

$\rho_{Al}r_{Al}^3 = \rho_{Fe}r_{Fe}^3$

</div>

Despejamos:

<div align="center">

$r_{Al}^3 = \frac{\rho_{Fe}}{\rho_{Al}}r_{Fe}^3$

</div>

Aplicamos raiz cubica:

<div align="center">

$r_{Al} = r_{Fe} \left(\frac{\rho_{Fe}}{\rho_{Al}}\right)^{1/3}$

</div>

Sustituimos:

<div align="center">

$r_{Al} = (2.00\,cm) \left( \frac{7.86\times10^3} {2.70\times10^3} \right)^{1/3}$

</div>

Se cancelan $10^3$:

<div align="center">

$r_{Al} = (2.00\,cm) \left( \frac{7.86}{2.70} \right)^{1/3}$

</div>

<div align="center">

$\boxed{r_{Al}\approx2.86\,cm}$

</div>

### Ejercicio 15 — Grosor de pintura

Datos:

<div align="center">

$V=3.78\times10^{-3}\,m^3$

</div>

<div align="center">

$A=25.0\,m^2$

</div>

Para una capa uniforme:

<div align="center">

$V=At$

</div>

Despejamos:

<div align="center">

$t=\frac{V}{A}$

</div>

Sustituimos:

<div align="center">

$t= \frac{3.78\times10^{-3}\,m^3} {25.0\,m^2}$

</div>

Se simplifican las unidades:

<div align="center">

$\frac{m^3}{m^2}=m$

</div>

Entonces:

<div align="center">

$t= \frac{3.78\times10^{-3}}{25.0}\,m$

</div>

<div align="center">

$\boxed{t=1.51\times10^{-4}\,m}$

</div>

En milimetros:

<div align="center">

$1\,m=1000\,mm$

</div>

<div align="center">

$t=(1.51\times10^{-4}\,m)(1000\,mm/m)$

</div>

<div align="center">

$\boxed{t=0.151\,mm}$

</div>

## Dato curioso

Un factor de conversion no altera la cantidad fisica porque su valor es exactamente uno; solamente cambia la forma en que expresamos esa cantidad.

## Ideas para recordar

- Decide primero que unidad quieres al final.
- Coloca el factor para que la unidad original se cancele.
- Lleva las unidades en todos los pasos.
- Si una unidad esta elevada a una potencia, el factor de conversion tambien debe elevarse.
