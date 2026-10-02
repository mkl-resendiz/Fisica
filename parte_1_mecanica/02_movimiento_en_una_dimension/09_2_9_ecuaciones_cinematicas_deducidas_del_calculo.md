# 2.9 Ecuaciones cinemáticas deducidas del cálculo

## Resumen

Esta sección conecta las definiciones de velocidad y aceleración con el cálculo diferencial e integral.

Velocidad:

\[
v_x=\frac{dx}{dt}
\]

Aceleración:

\[
a_x=\frac{dv_x}{dt}
\]

Si se conoce \(v_x(t)\), el desplazamiento puede obtenerse mediante:

\[
\Delta x=
\int_{t_i}^{t_f}v_x(t)\,dt
\]

La interpretación geométrica es que el desplazamiento corresponde al área bajo la gráfica velocidad-tiempo, considerando el signo.

## Deducción de la ecuación de velocidad

Partimos de:

\[
a_x=\frac{dv_x}{dt}
\]

Multiplicamos por \(dt\):

\[
dv_x=a_x\,dt
\]

Integramos:

\[
\int_{v_{xi}}^{v_{xf}}dv_x
=
\int_0^t a_x\,dt
\]

Si \(a_x\) es constante:

\[
v_{xf}-v_{xi}
=
a_x\int_0^t dt
\]

\[
v_{xf}-v_{xi}=a_xt
\]

Sumamos \(v_{xi}\) a ambos lados:

\[
\boxed{v_{xf}=v_{xi}+a_xt}
\]

Esta es la ecuación 2.13.

## Deducción de la ecuación de posición

Partimos de:

\[
v_x=\frac{dx}{dt}
\]

\[
dx=v_x\,dt
\]

Integramos:

\[
x_f-x_i=\int_0^t v_x\,dt
\]

Para aceleración constante:

\[
v_x=v_{xi}+a_xt
\]

Entonces:

\[
x_f-x_i=
\int_0^t(v_{xi}+a_xt)\,dt
\]

Separamos:

\[
x_f-x_i=
\int_0^t v_{xi}\,dt
+
a_x\int_0^t t\,dt
\]

Evaluamos:

\[
x_f-x_i=
v_{xi}t+\frac12a_xt^2
\]

Por tanto:

\[
\boxed{x_f=x_i+v_{xi}t+\frac12a_xt^2}
\]

Esta es la ecuación 2.16.

## Ejercicios representativos

### Ejercicio 1 — Problema 34

El área bajo una gráfica \(v_x-t\) representa desplazamiento.

Para aceleración constante, la gráfica es una recta. El área se puede separar en:

- rectángulo:

\[
A_R=v_{xi}t
\]

- triángulo:

\[
A_T=\frac12(v_{xf}-v_{xi})t
\]

Sumamos:

\[
\Delta x
=
v_{xi}t+
\frac12(v_{xf}-v_{xi})t
\]

Distribuimos:

\[
\Delta x
=
v_{xi}t+
\frac12v_{xf}t-
\frac12v_{xi}t
\]

Agrupamos:

\[
\Delta x=
\frac12v_{xi}t+
\frac12v_{xf}t
\]

\[
\boxed{
\Delta x=
\frac12(v_{xi}+v_{xf})t
}
\]

que corresponde a la ecuación 2.15.

### Ejercicio 2 — Problema 35

El insecto acelera:

\[
a=4.00\,\mathrm{km/s^2}
\]

durante:

\[
\Delta x=2.00\,\mathrm{mm}
=2.00\times10^{-3}\,\mathrm{m}
\]

Convertimos:

\[
4.00\,\mathrm{km/s^2}
=
4.00\times10^3\,\mathrm{m/s^2}
\]

Partiendo del reposo:

\[
v_i=0
\]

Usamos:

\[
v_f^2=v_i^2+2a\Delta x
\]

\[
v_f^2=
0+2(4.00\times10^3)(2.00\times10^{-3})
\]

\[
v_f^2=16.0\,\mathrm{m^2/s^2}
\]

\[
v_f=\sqrt{16.0\,\mathrm{m^2/s^2}}
\]

\[
\boxed{v_f=4.00\,\mathrm{m/s}}
\]

Tiempo:

\[
v_f=v_i+at
\]

\[
t=\frac{v_f-v_i}{a}
\]

\[
t=
\frac{4.00\,\mathrm{m/s}}
{4.00\times10^3\,\mathrm{m/s^2}}
\]

\[
\boxed{t=1.00\times10^{-3}\,\mathrm{s}}
\]

### Ejercicio 3 — Área bajo \(v(t)\)

Si una partícula mantiene:

\[
v_x=5.00\,\mathrm{m/s}
\]

durante:

\[
\Delta t=4.00\,\mathrm{s}
\]

la integral:

\[
\Delta x=\int_{0}^{4}5.00\,dt
\]

corresponde al área de un rectángulo:

\[
\Delta x=(5.00\,\mathrm{m/s})(4.00\,\mathrm{s})
\]

\[
\boxed{\Delta x=20.0\,\mathrm{m}}
\]

## Dato curioso

La sección muestra una conexión poderosa: el área bajo una gráfica velocidad-tiempo no es sólo una representación geométrica; tiene directamente unidades de longitud y representa el desplazamiento.
