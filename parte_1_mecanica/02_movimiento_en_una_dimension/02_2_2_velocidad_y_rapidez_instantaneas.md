# 2.2 Velocidad y rapidez instantáneas

## Resumen

La velocidad promedio describe un intervalo completo. Para conocer la velocidad **en un instante**, se hace el intervalo cada vez menor:

<div align="center">

$v_x=\lim_{\Delta t\to0}\frac{\Delta x}{\Delta t} =\frac{dx}{dt}$

</div>

Geométricamente, la velocidad instantánea es la **pendiente de la recta tangente** a la gráfica $x-t$.

La rapidez instantánea es la magnitud de la velocidad:

<div align="center">

$v=|v_x|$

</div>

## Ejemplo 2.3

La posición de una partícula está dada por:

<div align="center">

$x=-4t+2t^2$

</div>

con $x$ en metros y $t$ en segundos.

### A. De $0$ a $1\,\mathrm{s}$

<div align="center">

$x_i=-4(0)+2(0)^2=0\,\mathrm{m}$

</div>

<div align="center">

$x_f=-4(1)+2(1)^2=-4+2=-2\,\mathrm{m}$

</div>

Entonces:

<div align="center">

$\Delta x=x_f-x_i=-2\,\mathrm{m}$

</div>

<div align="center">

$\Delta t=1\,\mathrm{s}$

</div>

<div align="center">

$v_{x,\mathrm{prom}} =\frac{-2\,\mathrm{m}}{1\,\mathrm{s}}$

</div>

<div align="center">

$\boxed{v_{x,\mathrm{prom}}=-2\,\mathrm{m/s}}$

</div>

### B. De $1$ a $3\,\mathrm{s}$

<div align="center">

$x_i=-4(1)+2(1)^2=-2\,\mathrm{m}$

</div>

<div align="center">

$x_f=-4(3)+2(3)^2=-12+18=6\,\mathrm{m}$

</div>

<div align="center">

$\Delta x=6-(-2)=8\,\mathrm{m}$

</div>

<div align="center">

$\Delta t=3-1=2\,\mathrm{s}$

</div>

<div align="center">

$v_{x,\mathrm{prom}} =\frac{8\,\mathrm{m}}{2\,\mathrm{s}}$

</div>

<div align="center">

$\boxed{v_{x,\mathrm{prom}}=4\,\mathrm{m/s}}$

</div>

### C. Velocidad instantánea en $t=2.5\,\mathrm{s}$

Partimos de:

<div align="center">

$v_x=\frac{dx}{dt}$

</div>

Derivamos:

<div align="center">

$x=-4t+2t^2$

</div>

<div align="center">

$\frac{dx}{dt} =-4+4t$

</div>

Por tanto:

<div align="center">

$v_x=-4+4t$

</div>

Sustituimos $t=2.5\,\mathrm{s}$:

<div align="center">

$v_x=-4+4(2.5)$

</div>

<div align="center">

$v_x=-4+10$

</div>

<div align="center">

$\boxed{v_x=6\,\mathrm{m/s}}$

</div>

**Interpretación:** la velocidad instantánea en ese instante apunta hacia $+x$.

## Ejercicios representativos

### Ejercicio 1 — Problema 4

Una nadadora recorre una piscina de longitud $L$ en tiempo $t_1$ y regresa al punto inicial en tiempo $t_2$.

Primera parte:

<div align="center">

$\Delta x=L$

</div>

<div align="center">

$\Delta t=t_1$

</div>

<div align="center">

$\boxed{v_{x,\mathrm{prom},1}=\frac{L}{t_1}}$

</div>

Segunda parte:

<div align="center">

$\Delta x=-L$

</div>

<div align="center">

$\Delta t=t_2-t_1$

</div>

<div align="center">

$\boxed{v_{x,\mathrm{prom},2}=-\frac{L}{t_2-t_1}}$

</div>

Recorrido completo:

<div align="center">

$\Delta x=0$

</div>

<div align="center">

$\Delta t=t_2$

</div>

<div align="center">

$\boxed{v_{x,\mathrm{prom},\mathrm{total}}=0}$

</div>

Rapidez promedio:

<div align="center">

$v_{\mathrm{prom}}=\frac{2L}{t_2}$

</div>

<div align="center">

$\boxed{v_{\mathrm{prom}}=\frac{2L}{t_2}}$

</div>

**Interpretación:** puede existir movimiento durante todo el recorrido y aun así la velocidad promedio ser cero si se regresa al punto inicial.

### Ejercicio 2 — Problema 5

La figura P2.5 proporciona una gráfica $x-t$. La velocidad promedio entre $1.50$ y $4.00\,\mathrm{s}$ se obtiene como:

<div align="center">

$v_{x,\mathrm{prom}} = \frac{x(4.00)-x(1.50)} {4.00-1.50}$

</div>

Los valores numéricos exactos deben leerse de la gráfica original; el PDF no proporciona aquí una tabla equivalente. Por ello, el procedimiento es la parte que puede resolverse de forma textual sin inventar datos.

### Ejercicio 3 — Velocidad a partir de posición

Si:

<div align="center">

$x=At^2$

</div>

donde $A$ es constante, entonces:

<div align="center">

$v_x=\frac{dx}{dt}$

</div>

Aplicando la regla de la potencia:

<div align="center">

$v_x=2At$

</div>

<div align="center">

$\boxed{v_x=2At}$

</div>

La velocidad cambia linealmente con el tiempo.

## Dato curioso

La idea de la velocidad instantánea es la transición conceptual entre medir “qué tan rápido ocurrió algo durante un intervalo” y describir exactamente el estado del movimiento en un instante. Matemáticamente, esta idea lleva directamente al concepto de derivada.
