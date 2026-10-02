# 2.8 Objetos en caída libre

## Resumen

En ausencia de resistencia del aire, un objeto cerca de la superficie terrestre se mueve bajo una aceleración gravitacional aproximadamente constante.

El libro usa:

$g=9.80\,\mathrm{m/s^2}$

y, tomando $+y$ hacia arriba:

$a_y=-g=-9.80\,\mathrm{m/s^2}$

Un objeto en caída libre no necesariamente parte del reposo: puede ser lanzado hacia arriba o hacia abajo.

## Ejemplo 2.10 — Piedra lanzada hacia arriba

Datos:

$v_{yi}=20.0\,\mathrm{m/s}$

$a_y=-9.80\,\mathrm{m/s^2}$

$y_i=0$

### A. Tiempo hasta la altura máxima

En la altura máxima:

$v_{yf}=0$

Partimos de:

$v_{yf}=v_{yi}+a_yt$

Despejamos:

$a_yt=v_{yf}-v_{yi}$

$t=\frac{v_{yf}-v_{yi}}{a_y}$

Sustitución:

$t= \frac{0-20.0\,\mathrm{m/s}} {-9.80\,\mathrm{m/s^2}}$

$\boxed{t=2.04\,\mathrm{s}}$

### B. Altura máxima

Usamos:

$y_f=y_i+v_{yi}t+\frac12a_yt^2$

Sustituimos:

$y_f= 0+(20.0)(2.04) +\frac12(-9.80)(2.04)^2$

$y_f\approx40.8-20.4$

$\boxed{y_{\max}\approx20.4\,\mathrm{m}}$

### C. Velocidad al regresar a la altura inicial

Usamos:

$v_{yf}^2=v_{yi}^2+2a_y(y_f-y_i)$

Como:

$y_f-y_i=0$

entonces:

$v_{yf}^2=(20.0)^2$

$v_{yf}=\pm20.0\,\mathrm{m/s}$

Como la piedra baja, elegimos la raíz negativa:

$\boxed{v_{yf}=-20.0\,\mathrm{m/s}}$

**Interpretación:** regresa con la misma magnitud de velocidad inicial, pero en dirección opuesta.

## Ejercicios representativos

### Ejercicio 1 — Problema 26

Una roca se lanza hacia arriba desde $1.55\,\mathrm{m}$ sobre el suelo con:

$v_i=7.40\,\mathrm{m/s}$

La parte superior está a:

$y_f=3.65\,\mathrm{m}$

Por tanto:

$\Delta y=3.65-1.55=2.10\,\mathrm{m}$

Usamos:

$v_f^2=v_i^2+2a_y\Delta y$

$v_f^2=(7.40)^2+2(-9.80)(2.10)$

$v_f^2=54.76-41.16=13.60$

$v_f=\sqrt{13.60}$

$\boxed{v_f\approx3.69\,\mathrm{m/s}}$

La velocidad sigue siendo positiva al llegar a la parte superior, así que sí alcanza la pared.

### Ejercicio 2 — Problema 28

Pelota A: se lanza desde el suelo con $25\,\mathrm{m/s}$.

Pelota B: se deja caer desde $15\,\mathrm{m}$.

Para A:

$y_A=25t-\frac12gt^2$

Para B:

$y_B=15-\frac12gt^2$

Cuando están a la misma altura:

$25t-\frac12gt^2 = 15-\frac12gt^2$

Los términos gravitacionales se cancelan:

$25t=15$

$\boxed{t=0.600\,\mathrm{s}}$

**Interpretación:** ambos objetos tienen la misma aceleración gravitacional, por eso los términos de aceleración se cancelan al comparar sus posiciones.

### Ejercicio 3 — Problema 29

Las llaves se atrapan a:

$y_f=4.00\,\mathrm{m}$

después de:

$t=1.50\,\mathrm{s}$

Con:

$y_i=0$

Usamos:

$y_f=y_i+v_{yi}t+\frac12a_yt^2$

Despejamos:

$v_{yi} = \frac{y_f-y_i-\frac12a_yt^2}{t}$

Como $a_y=-g$:

$v_{yi} = \frac{4.00-\frac12(-9.80)(1.50)^2} {1.50}$

$v_{yi} = \frac{4.00+11.025}{1.50}$

$\boxed{v_{yi}\approx10.0\,\mathrm{m/s}}$

Velocidad justo antes de atraparlas:

$v_{yf}=v_{yi}+a_yt$

$v_{yf}=10.0-(9.80)(1.50)$

$\boxed{v_{yf}\approx-4.70\,\mathrm{m/s}}$

El signo negativo indica movimiento hacia abajo.

## Dato curioso

El 2 de agosto de 1971, David Scott realizó en la Luna una demostración soltando simultáneamente un martillo y una pluma. Sin una atmósfera significativa, ambos cayeron con la misma aceleración gravitacional.
