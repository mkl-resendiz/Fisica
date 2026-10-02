# 2.7 Modelo de análisis: la partícula bajo aceleración constante

## Resumen

Cuando la aceleración es constante, el movimiento en una dimensión se describe con cinco ecuaciones cinemáticas:

<div align="center">

$v_{xf}=v_{xi}+a_xt \tag{2.13}$

</div>

<div align="center">

$v_{x,\mathrm{prom}}= \frac{v_{xi}+v_{xf}}{2} \tag{2.14}$

</div>

<div align="center">

$x_f=x_i+\frac12(v_{xi}+v_{xf})t \tag{2.15}$

</div>

<div align="center">

$x_f=x_i+v_{xi}t+\frac12a_xt^2 \tag{2.16}$

</div>

<div align="center">

$v_{xf}^2=v_{xi}^2+2a_x(x_f-x_i) \tag{2.17}$

</div>

La elección depende de qué variables sean conocidas.

## Ejemplo 2.7 — Aterrizaje en portaaviones

Un jet aterriza a $63\,\mathrm{m/s}$ y se detiene en $2.0\,\mathrm{s}$.

### A. Aceleración

Datos:

<div align="center">

$v_{xi}=63\,\mathrm{m/s}$

</div>

<div align="center">

$v_{xf}=0\,\mathrm{m/s}$

</div>

<div align="center">

$t=2.0\,\mathrm{s}$

</div>

Partimos de:

<div align="center">

$v_{xf}=v_{xi}+a_xt$

</div>

Despejamos:

<div align="center">

$a_xt=v_{xf}-v_{xi}$

</div>

<div align="center">

$a_x=\frac{v_{xf}-v_{xi}}{t}$

</div>

Sustituimos:

<div align="center">

$a_x= \frac{0-63\,\mathrm{m/s}} {2.0\,\mathrm{s}}$

</div>

<div align="center">

$\boxed{a_x=-31.5\,\mathrm{m/s^2}\approx-32\,\mathrm{m/s^2}}$

</div>

### B. Posición final

Con $x_i=0$:

<div align="center">

$x_f=x_i+\frac12(v_{xi}+v_{xf})t$

</div>

<div align="center">

$x_f= 0+\frac12(63+0)(2.0)$

</div>

<div align="center">

$x_f=63\,\mathrm{m}$

</div>

<div align="center">

$\boxed{x_f=63\,\mathrm{m}}$

</div>

**Interpretación:** el cable detiene al jet en aproximadamente $63\,\mathrm{m}$.

## Ejemplo 2.8 — Patrullero

El automóvil pasa al patrullero a $45.0\,\mathrm{m/s}$. Un segundo después, el patrullero parte del reposo con:

<div align="center">

$a_x=3.00\,\mathrm{m/s^2}$

</div>

El origen se coloca en el anuncio y el tiempo cero cuando parte el patrullero.

Automóvil:

<div align="center">

$x_{\mathrm{auto}} = 45.0\,\mathrm{m} +(45.0\,\mathrm{m/s})t$

</div>

Patrullero:

<div align="center">

$x_{\mathrm{patrullero}} = \frac12(3.00\,\mathrm{m/s^2})t^2$

</div>

En el alcance:

<div align="center">

$x_{\mathrm{auto}}=x_{\mathrm{patrullero}}$

</div>

<div align="center">

$45.0+45.0t=1.50t^2$

</div>

La solución física positiva es:

<div align="center">

$\boxed{t\approx31.0\,\mathrm{s}}$

</div>

## Ejercicios representativos

### Ejercicio 1 — Problema 14

Un electrón aumenta su rapidez de $2.00\times10^4$ a $6.00\times10^6\,\mathrm{m/s}$ en $1.50\,\mathrm{cm}$.

Convertimos:

<div align="center">

$1.50\,\mathrm{cm}=0.0150\,\mathrm{m}$

</div>

Usamos:

<div align="center">

$v_{xf}^2=v_{xi}^2+2a_x\Delta x$

</div>

Despejamos:

<div align="center">

$2a_x\Delta x=v_{xf}^2-v_{xi}^2$

</div>

<div align="center">

$a_x= \frac{v_{xf}^2-v_{xi}^2}{2\Delta x}$

</div>

Sustitución:

<div align="center">

$a_x= \frac{(6.00\times10^6)^2-(2.00\times10^4)^2} {2(0.0150)}$

</div>

<div align="center">

$a_x\approx1.20\times10^{15}\,\mathrm{m/s^2}$

</div>

<div align="center">

$\boxed{a_x\approx1.20\times10^{15}\,\mathrm{m/s^2}}$

</div>

Para el tiempo:

<div align="center">

$v_{xf}=v_{xi}+a_xt$

</div>

Despejamos:

<div align="center">

$t=\frac{v_{xf}-v_{xi}}{a_x}$

</div>

<div align="center">

$t= \frac{6.00\times10^6-2.00\times10^4} {1.20\times10^{15}}$

</div>

<div align="center">

$\boxed{t\approx5.0\times10^{-9}\,\mathrm{s}}$

</div>

### Ejercicio 2 — Problema 16

Un jet tiene $v_i=100\,\mathrm{m/s}$ y una aceleración máxima de frenado de magnitud $5.00\,\mathrm{m/s^2}$.

Para minimizar el tiempo de detención usamos:

<div align="center">

$v_f=v_i+a_xt$

</div>

Con:

<div align="center">

$v_f=0,\qquad a_x=-5.00\,\mathrm{m/s^2}$

</div>

<div align="center">

$0=100-5.00t$

</div>

<div align="center">

$5.00t=100$

</div>

<div align="center">

$\boxed{t=20.0\,\mathrm{s}}$

</div>

Distancia:

<div align="center">

$v_f^2=v_i^2+2a_x\Delta x$

</div>

<div align="center">

$0=(100)^2+2(-5.00)\Delta x$

</div>

<div align="center">

$10\Delta x=10000$

</div>

<div align="center">

$\boxed{\Delta x=1000\,\mathrm{m}=1.00\,\mathrm{km}}$

</div>

Como la pista mide $0.800\,\mathrm{km}$, no alcanza para detenerse bajo estas condiciones.

### Ejercicio 3 — Problema 17

Datos:

<div align="center">

$v_i=12.0\,\mathrm{cm/s}$

</div>

<div align="center">

$x_i=3.00\,\mathrm{cm}$

</div>

<div align="center">

$x_f=-5.00\,\mathrm{cm}$

</div>

<div align="center">

$t=2.00\,\mathrm{s}$

</div>

Usamos:

<div align="center">

$x_f=x_i+v_it+\frac12a_xt^2$

</div>

Sustituimos:

<div align="center">

$-5.00 = 3.00+(12.0)(2.00) +\frac12a_x(2.00)^2$

</div>

<div align="center">

$-5.00=27.0+2a_x$

</div>

<div align="center">

$2a_x=-32.0$

</div>

<div align="center">

$\boxed{a_x=-16.0\,\mathrm{cm/s^2}}$

</div>

**Interpretación:** la aceleración apunta en la dirección negativa de $x$.

## Dato curioso

Las cinco ecuaciones cinemáticas no son cinco leyes independientes: describen distintas relaciones de un mismo modelo físico. La elección correcta depende de qué variables estén disponibles.
