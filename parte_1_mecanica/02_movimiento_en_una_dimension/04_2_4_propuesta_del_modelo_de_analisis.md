# 2.4 Propuesta del modelo de análisis para resolver problemas

## Resumen

El capítulo propone una estrategia general de resolución:

1. **Conceptualizar:** entender la situación y construir una representación mental o dibujo.
2. **Categorizar:** identificar el modelo de análisis apropiado.
3. **Analizar:** seleccionar y aplicar las ecuaciones del modelo.
4. **Finalizar:** comprobar unidades, signos, magnitud y coherencia física.

La idea central es **identificar primero el modelo**, en lugar de buscar una ecuación al azar.

## Ejemplo de aplicación

El ejemplo del corredor de la sección anterior se puede organizar con los cuatro pasos:

### 1. Conceptualizar

El corredor se representa como una partícula que recorre una línea recta.

Datos:

\[
\Delta x=20\,\mathrm{m}
\]

\[
\Delta t=4.0\,\mathrm{s}
\]

y la rapidez es constante.

### 2. Categorizar

La condición “rapidez constante” permite utilizar el modelo de partícula bajo velocidad constante.

### 3. Analizar

\[
v_x=\frac{\Delta x}{\Delta t}
\]

\[
v_x=\frac{20\,\mathrm{m}}{4.0\,\mathrm{s}}
=5.0\,\mathrm{m/s}
\]

Para \(t=10\,\mathrm{s}\):

\[
x_f=x_i+v_xt
\]

\[
x_f=0+(5.0\,\mathrm{m/s})(10\,\mathrm{s})
=50\,\mathrm{m}
\]

### 4. Finalizar

Las unidades son correctas:

\[
\frac{\mathrm{m}}{\mathrm{s}}=\mathrm{m/s}
\]

y la posición de \(50\,\mathrm{m}\) es coherente con mantener \(5.0\,\mathrm{m/s}\) durante \(10\,\mathrm{s}\).

## Ejercicios representativos

### Ejercicio 1 — Elegir el modelo

Un automóvil recorre una carretera recta con rapidez constante.

**Conceptualizar:** movimiento unidimensional.

**Categorizar:** partícula bajo velocidad constante.

**Analizar:**

\[
x_f=x_i+v_xt
\]

**Finalizar:** verificar que \(v_x t\) tenga unidades de longitud.

### Ejercicio 2 — Reconocer cuándo NO usar el modelo

Si la velocidad cambia con el tiempo, no debe utilizarse directamente:

\[
x_f=x_i+v_xt
\]

con un único valor de \(v_x\), porque esa ecuación pertenece al modelo de velocidad constante.

En ese caso hay que identificar otro modelo, por ejemplo el de aceleración constante si la aceleración permanece constante.

### Ejercicio 3 — Problema 18

El problema 18 propone resolver gráficamente el ejemplo 2.8, trazando posición contra tiempo para el automóvil y el oficial.

El procedimiento es:

**Automóvil:**

\[
x_{\mathrm{auto}}=45.0\,\mathrm{m}+(45.0\,\mathrm{m/s})t
\]

**Patrullero:**

\[
x_{\mathrm{policía}}=
\frac12(3.00\,\mathrm{m/s^2})t^2
\]

El alcance ocurre cuando:

\[
x_{\mathrm{auto}}=x_{\mathrm{policía}}
\]

Por tanto:

\[
45.0+45.0t=1.50t^2
\]

La intersección positiva de ambas curvas corresponde al instante de alcance.

El ejemplo del libro obtiene:

\[
\boxed{t\approx31.0\,\mathrm{s}}
\]

**Interpretación:** el método gráfico y el algebraico representan la misma condición física: ambos vehículos ocupan la misma posición en el mismo instante.

## Dato curioso

El libro destaca que aprender a categorizar un problema es una habilidad transferible: en lugar de memorizar una ecuación para cada situación, se identifica primero el comportamiento físico.
