# 2.2 Velocidad y rapidez instantáneas

## Resumen

La velocidad promedio describe un intervalo completo. Para conocer la velocidad **en un instante**, se hace el intervalo cada vez menor:

$v_x=\lim_{\Delta t\to0}\frac{\Delta x}{\Delta t} =\frac{dx}{dt}$

Geométricamente, la velocidad instantánea es la **pendiente de la recta tangente** a la gráfica $x-t$.

La rapidez instantánea es la magnitud de la velocidad:

$v=|v_x|$

## Ejemplo 2.3

La posición de una partícula está dada por:

$x=-4t+2t^2$

con $x$ en metros y $t$ en segundos.

### A. De $0$ a $1\,\mathrm{s}$

$x_i=-4(0)+2(0)^2=0\,\mathrm{m}$

$x_f=-4(1)+2(1)^2=-4+2=-2\,\mathrm{m}$

Entonces:

$\Delta x=x_f-x_i=-2\,\mathrm{m}$

$\Delta t=1\,\mathrm{s}$

$v_{x,\mathrm{prom}} =\frac{-2\,\mathrm{m}}{1\,\mathrm{s}}$

$\boxed{v_{x,\mathrm{prom}}=-2\,\mathrm{m/s}}$

### B. De $1$ a $3\,\mathrm{s}$

$x_i=-4(1)+2(1)^2=-2\,\mathrm{m}$

$x_f=-4(3)+2(3)^2=-12+18=6\,\mathrm{m}$

$\Delta x=6-(-2)=8\,\mathrm{m}$

$\Delta t=3-1=2\,\mathrm{s}$

$v_{x,\mathrm{prom}} =\frac{8\,\mathrm{m}}{2\,\mathrm{s}}$

$\boxed{v_{x,\mathrm{prom}}=4\,\mathrm{m/s}}$

### C. Velocidad instantánea en $t=2.5\,\mathrm{s}$

Partimos de:

$v_x=\frac{dx}{dt}$

Derivamos:

$x=-4t+2t^2$

$\frac{dx}{dt} =-4+4t$

Por tanto:

$v_x=-4+4t$

Sustituimos $t=2.5\,\mathrm{s}$:

$v_x=-4+4(2.5)$

$v_x=-4+10$

$\boxed{v_x=6\,\mathrm{m/s}}$

**Interpretación:** la velocidad instantánea en ese instante apunta hacia $+x$.

## Ejercicios representativos

### Ejercicio 1 — Problema 4

Una nadadora recorre una piscina de longitud $L$ en tiempo $t_1$ y regresa al punto inicial en tiempo $t_2$.

Primera parte:

$\Delta x=L$

$\Delta t=t_1$

$\boxed{v_{x,\mathrm{prom},1}=\frac{L}{t_1}}$

Segunda parte:

$\Delta x=-L$

$\Delta t=t_2-t_1$

$\boxed{v_{x,\mathrm{prom},2}=-\frac{L}{t_2-t_1}}$

Recorrido completo:

$\Delta x=0$

$\Delta t=t_2$

$\boxed{v_{x,\mathrm{prom},\mathrm{total}}=0}$

Rapidez promedio:

$v_{\mathrm{prom}}=\frac{2L}{t_2}$

$\boxed{v_{\mathrm{prom}}=\frac{2L}{t_2}}$

**Interpretación:** puede existir movimiento durante todo el recorrido y aun así la velocidad promedio ser cero si se regresa al punto inicial.

### Ejercicio 2 — Problema 5

La figura P2.5 proporciona una gráfica $x-t$. La velocidad promedio entre $1.50$ y $4.00\,\mathrm{s}$ se obtiene como:

$v_{x,\mathrm{prom}} = \frac{x(4.00)-x(1.50)} {4.00-1.50}$

Los valores numéricos exactos deben leerse de la gráfica original; el PDF no proporciona aquí una tabla equivalente. Por ello, el procedimiento es la parte que puede resolverse de forma textual sin inventar datos.

### Ejercicio 3 — Velocidad a partir de posición

Si:

$x=At^2$

donde $A$ es constante, entonces:

$v_x=\frac{dx}{dt}$

Aplicando la regla de la potencia:

$v_x=2At$

$\boxed{v_x=2At}$

La velocidad cambia linealmente con el tiempo.

## Dato curioso

La idea de la velocidad instantánea es la transición conceptual entre medir “qué tan rápido ocurrió algo durante un intervalo” y describir exactamente el estado del movimiento en un instante. Matemáticamente, esta idea lleva directamente al concepto de derivada.
