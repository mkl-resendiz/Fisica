# 2.5 Aceleración

## Resumen

Cuando la velocidad cambia con el tiempo, la partícula acelera.

Aceleración promedio:

<div align="center">

$a_{x,\mathrm{prom}} = \frac{\Delta v_x}{\Delta t} = \frac{v_{xf}-v_{xi}}{t_f-t_i}$

</div>

Aceleración instantánea:

<div align="center">

$a_x= \lim_{\Delta t\to0} \frac{\Delta v_x}{\Delta t} = \frac{dv_x}{dt}$

</div>

Como:

<div align="center">

$v_x=\frac{dx}{dt}$

</div>

también:

<div align="center">

$a_x=\frac{d^2x}{dt^2}$

</div>

La unidad SI es:

<div align="center">

$\mathrm{m/s^2}$

</div>

Es importante no interpretar “aceleración negativa” como sinónimo de “frenar”. Si velocidad y aceleración tienen el mismo signo, la rapidez aumenta; si tienen signos opuestos, la rapidez disminuye.

## Ejemplo 2.6 — Aceleración promedio e instantánea

Se da:

<div align="center">

$v_x=40-5t^2$

</div>

con $v_x$ en $\mathrm{m/s}$ y $t$ en segundos.

### A. Aceleración promedio de $0$ a $2.0\,\mathrm{s}$

Velocidad inicial:

<div align="center">

$v_{xi}=40-5(0)^2=40\,\mathrm{m/s}$

</div>

Velocidad final:

<div align="center">

$v_{xf}=40-5(2.0)^2$

</div>

<div align="center">

$=40-20=20\,\mathrm{m/s}$

</div>

Ecuación:

<div align="center">

$a_{x,\mathrm{prom}} = \frac{v_{xf}-v_{xi}} {t_f-t_i}$

</div>

Sustitución:

<div align="center">

$a_{x,\mathrm{prom}} = \frac{20-40} {2.0-0}$

</div>

<div align="center">

$=\frac{-20\,\mathrm{m/s}}{2.0\,\mathrm{s}}$

</div>

<div align="center">

$\boxed{a_{x,\mathrm{prom}}=-10\,\mathrm{m/s^2}}$

</div>

### B. Aceleración instantánea en $t=2.0\,\mathrm{s}$

Partimos de:

<div align="center">

$a_x=\frac{dv_x}{dt}$

</div>

Derivamos:

<div align="center">

$v_x=40-5t^2$

</div>

<div align="center">

$a_x=-10t$

</div>

Sustituimos:

<div align="center">

$a_x=(-10)(2.0)$

</div>

<div align="center">

$\boxed{a_x=-20\,\mathrm{m/s^2}}$

</div>

**Interpretación:** la aceleración instantánea y la promedio no son iguales porque la aceleración no es constante.

## Ejercicios representativos

### Ejercicio 1 — Problema 9

Para una gráfica $v_x-t$, la aceleración promedio entre $0$ y $6.00\,\mathrm{s}$ se obtiene mediante:

<div align="center">

$a_{x,\mathrm{prom}} = \frac{v_x(6.00)-v_x(0)} {6.00\,\mathrm{s}}$

</div>

Los valores de $v_x$ deben leerse de la gráfica P2.9. El procedimiento es directo, pero no se asignan aquí valores que no aparecen en el texto extraído.

### Ejercicio 2 — Derivada de una función de posición

Si:

<div align="center">

$x=At^n$

</div>

entonces:

<div align="center">

$v_x=\frac{dx}{dt}=nAt^{n-1}$

</div>

y:

<div align="center">

$a_x=\frac{dv_x}{dt} =n(n-1)At^{n-2}$

</div>

Por tanto:

<div align="center">

$\boxed{a_x=n(n-1)At^{n-2}}$

</div>

### Ejercicio 3 — Relación entre signos

Suponga:

<div align="center">

$v_x=-8\,\mathrm{m/s}$

</div>

y:

<div align="center">

$a_x=-2\,\mathrm{m/s^2}$

</div>

Ambas cantidades tienen signo negativo y, por tanto, apuntan en la misma dirección.

La rapidez aumenta porque velocidad y aceleración tienen la misma dirección.

**Conclusión:**

<div align="center">

$\boxed{\text{el objeto aumenta su rapidez}}$

</div>

Esto muestra por qué una aceleración negativa no significa necesariamente que el objeto esté frenando.

## Dato curioso

El libro evita utilizar “desaceleración” como término técnico porque puede generar confusión: lo físicamente relevante es comparar la dirección de la velocidad con la dirección de la aceleración.
