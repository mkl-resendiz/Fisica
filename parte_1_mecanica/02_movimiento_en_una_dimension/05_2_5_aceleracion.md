# 2.5 Aceleración

## Resumen

Cuando la velocidad cambia con el tiempo, la partícula acelera.

Aceleración promedio:

$a_{x,\mathrm{prom}} = \frac{\Delta v_x}{\Delta t} = \frac{v_{xf}-v_{xi}}{t_f-t_i}$

Aceleración instantánea:

$a_x= \lim_{\Delta t\to0} \frac{\Delta v_x}{\Delta t} = \frac{dv_x}{dt}$

Como:

$v_x=\frac{dx}{dt}$

también:

$a_x=\frac{d^2x}{dt^2}$

La unidad SI es:

$\mathrm{m/s^2}$

Es importante no interpretar “aceleración negativa” como sinónimo de “frenar”. Si velocidad y aceleración tienen el mismo signo, la rapidez aumenta; si tienen signos opuestos, la rapidez disminuye.

## Ejemplo 2.6 — Aceleración promedio e instantánea

Se da:

$v_x=40-5t^2$

con $v_x$ en $\mathrm{m/s}$ y $t$ en segundos.

### A. Aceleración promedio de $0$ a $2.0\,\mathrm{s}$

Velocidad inicial:

$v_{xi}=40-5(0)^2=40\,\mathrm{m/s}$

Velocidad final:

$v_{xf}=40-5(2.0)^2$

$=40-20=20\,\mathrm{m/s}$

Ecuación:

$a_{x,\mathrm{prom}} = \frac{v_{xf}-v_{xi}} {t_f-t_i}$

Sustitución:

$a_{x,\mathrm{prom}} = \frac{20-40} {2.0-0}$

$=\frac{-20\,\mathrm{m/s}}{2.0\,\mathrm{s}}$

$\boxed{a_{x,\mathrm{prom}}=-10\,\mathrm{m/s^2}}$

### B. Aceleración instantánea en $t=2.0\,\mathrm{s}$

Partimos de:

$a_x=\frac{dv_x}{dt}$

Derivamos:

$v_x=40-5t^2$

$a_x=-10t$

Sustituimos:

$a_x=(-10)(2.0)$

$\boxed{a_x=-20\,\mathrm{m/s^2}}$

**Interpretación:** la aceleración instantánea y la promedio no son iguales porque la aceleración no es constante.

## Ejercicios representativos

### Ejercicio 1 — Problema 9

Para una gráfica $v_x-t$, la aceleración promedio entre $0$ y $6.00\,\mathrm{s}$ se obtiene mediante:

$a_{x,\mathrm{prom}} = \frac{v_x(6.00)-v_x(0)} {6.00\,\mathrm{s}}$

Los valores de $v_x$ deben leerse de la gráfica P2.9. El procedimiento es directo, pero no se asignan aquí valores que no aparecen en el texto extraído.

### Ejercicio 2 — Derivada de una función de posición

Si:

$x=At^n$

entonces:

$v_x=\frac{dx}{dt}=nAt^{n-1}$

y:

$a_x=\frac{dv_x}{dt} =n(n-1)At^{n-2}$

Por tanto:

$\boxed{a_x=n(n-1)At^{n-2}}$

### Ejercicio 3 — Relación entre signos

Suponga:

$v_x=-8\,\mathrm{m/s}$

y:

$a_x=-2\,\mathrm{m/s^2}$

Ambas cantidades tienen signo negativo y, por tanto, apuntan en la misma dirección.

La rapidez aumenta porque velocidad y aceleración tienen la misma dirección.

**Conclusión:**

$\boxed{\text{el objeto aumenta su rapidez}}$

Esto muestra por qué una aceleración negativa no significa necesariamente que el objeto esté frenando.

## Dato curioso

El libro evita utilizar “desaceleración” como término técnico porque puede generar confusión: lo físicamente relevante es comparar la dirección de la velocidad con la dirección de la aceleración.
