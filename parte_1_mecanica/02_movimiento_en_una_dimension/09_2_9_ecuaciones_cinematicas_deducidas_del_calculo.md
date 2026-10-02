# 2.9 Ecuaciones cinemáticas deducidas del cálculo

## Resumen

Esta sección conecta las definiciones de velocidad y aceleración con el cálculo diferencial e integral.

Velocidad:

<div align="center">

$v_x=\frac{dx}{dt}$

</div>

Aceleración:

<div align="center">

$a_x=\frac{dv_x}{dt}$

</div>

Si se conoce $v_x(t)$, el desplazamiento puede obtenerse mediante:

<div align="center">

$\Delta x= \int_{t_i}^{t_f}v_x(t)\,dt$

</div>

La interpretación geométrica es que el desplazamiento corresponde al área bajo la gráfica velocidad-tiempo, considerando el signo.

## Deducción de la ecuación de velocidad

Partimos de:

<div align="center">

$a_x=\frac{dv_x}{dt}$

</div>

Multiplicamos por $dt$:

<div align="center">

$dv_x=a_x\,dt$

</div>

Integramos:

<div align="center">

$\int_{v_{xi}}^{v_{xf}}dv_x = \int_0^t a_x\,dt$

</div>

Si $a_x$ es constante:

<div align="center">

$v_{xf}-v_{xi} = a_x\int_0^t dt$

</div>

<div align="center">

$v_{xf}-v_{xi}=a_xt$

</div>

Sumamos $v_{xi}$ a ambos lados:

<div align="center">

$\boxed{v_{xf}=v_{xi}+a_xt}$

</div>

Esta es la ecuación 2.13.

## Deducción de la ecuación de posición

Partimos de:

<div align="center">

$v_x=\frac{dx}{dt}$

</div>

<div align="center">

$dx=v_x\,dt$

</div>

Integramos:

<div align="center">

$x_f-x_i=\int_0^t v_x\,dt$

</div>

Para aceleración constante:

<div align="center">

$v_x=v_{xi}+a_xt$

</div>

Entonces:

<div align="center">

$x_f-x_i= \int_0^t(v_{xi}+a_xt)\,dt$

</div>

Separamos:

<div align="center">

$x_f-x_i= \int_0^t v_{xi}\,dt + a_x\int_0^t t\,dt$

</div>

Evaluamos:

<div align="center">

$x_f-x_i= v_{xi}t+\frac12a_xt^2$

</div>

Por tanto:

<div align="center">

$\boxed{x_f=x_i+v_{xi}t+\frac12a_xt^2}$

</div>

Esta es la ecuación 2.16.

## Ejercicios representativos

### Ejercicio 1 — Problema 34

El área bajo una gráfica $v_x-t$ representa desplazamiento.

Para aceleración constante, la gráfica es una recta. El área se puede separar en:

- rectángulo:

<div align="center">

$A_R=v_{xi}t$

</div>

- triángulo:

<div align="center">

$A_T=\frac12(v_{xf}-v_{xi})t$

</div>

Sumamos:

<div align="center">

$\Delta x = v_{xi}t+ \frac12(v_{xf}-v_{xi})t$

</div>

Distribuimos:

<div align="center">

$\Delta x = v_{xi}t+ \frac12v_{xf}t- \frac12v_{xi}t$

</div>

Agrupamos:

<div align="center">

$\Delta x= \frac12v_{xi}t+ \frac12v_{xf}t$

</div>

<div align="center">

$\boxed{ \Delta x= \frac12(v_{xi}+v_{xf})t }$

</div>

que corresponde a la ecuación 2.15.

### Ejercicio 2 — Problema 35

El insecto acelera:

<div align="center">

$a=4.00\,\mathrm{km/s^2}$

</div>

durante:

<div align="center">

$\Delta x=2.00\,\mathrm{mm} =2.00\times10^{-3}\,\mathrm{m}$

</div>

Convertimos:

<div align="center">

$4.00\,\mathrm{km/s^2} = 4.00\times10^3\,\mathrm{m/s^2}$

</div>

Partiendo del reposo:

<div align="center">

$v_i=0$

</div>

Usamos:

<div align="center">

$v_f^2=v_i^2+2a\Delta x$

</div>

<div align="center">

$v_f^2= 0+2(4.00\times10^3)(2.00\times10^{-3})$

</div>

<div align="center">

$v_f^2=16.0\,\mathrm{m^2/s^2}$

</div>

<div align="center">

$v_f=\sqrt{16.0\,\mathrm{m^2/s^2}}$

</div>

<div align="center">

$\boxed{v_f=4.00\,\mathrm{m/s}}$

</div>

Tiempo:

<div align="center">

$v_f=v_i+at$

</div>

<div align="center">

$t=\frac{v_f-v_i}{a}$

</div>

<div align="center">

$t= \frac{4.00\,\mathrm{m/s}} {4.00\times10^3\,\mathrm{m/s^2}}$

</div>

<div align="center">

$\boxed{t=1.00\times10^{-3}\,\mathrm{s}}$

</div>

### Ejercicio 3 — Área bajo $v(t)$

Si una partícula mantiene:

<div align="center">

$v_x=5.00\,\mathrm{m/s}$

</div>

durante:

<div align="center">

$\Delta t=4.00\,\mathrm{s}$

</div>

la integral:

<div align="center">

$\Delta x=\int_{0}^{4}5.00\,dt$

</div>

corresponde al área de un rectángulo:

<div align="center">

$\Delta x=(5.00\,\mathrm{m/s})(4.00\,\mathrm{s})$

</div>

<div align="center">

$\boxed{\Delta x=20.0\,\mathrm{m}}$

</div>

## Dato curioso

La sección muestra una conexión poderosa: el área bajo una gráfica velocidad-tiempo no es sólo una representación geométrica; tiene directamente unidades de longitud y representa el desplazamiento.
