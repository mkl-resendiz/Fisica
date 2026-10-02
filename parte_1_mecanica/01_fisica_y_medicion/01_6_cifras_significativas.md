# 1.6 Cifras significativas

## Resumen

Las mediciones experimentales tienen incertidumbre. Las cifras significativas indican la precision que realmente esta contenida en una medicion.

Para multiplicacion y division, el resultado conserva el numero de cifras significativas de la cantidad con menos cifras significativas.

Para suma y resta, el resultado conserva el menor numero de lugares decimales.

El libro tambien recomienda conservar todos los digitos durante los calculos intermedios y redondear solamente al final.

## Conceptos clave

- Incertidumbre.
- Cifras significativas.
- Lugares decimales.
- Notacion cientifica.
- Redondeo.
- Precision.

## Formulas importantes

### Area de un rectangulo

<div align="center">

$A=LW$

</div>

### Area de un circulo

<div align="center">

$A=\pi r^2$

</div>

Para multiplicar:

<div align="center">

$\text{cifras significativas del resultado} = \text{menor numero de cifras significativas de los datos}$

</div>

Para sumar o restar:

<div align="center">

$\text{lugares decimales del resultado} = \text{menor numero de lugares decimales de los datos}$

</div>

## Ejemplo del libro

### Problema

Una habitacion mide:

<div align="center">

$L=12.71\,m$

</div>

<div align="center">

$W=3.46\,m$

</div>

Encontrar el area.

### Que se busca

<div align="center">

$A=?$

</div>

### Principio fisico

El area de un rectangulo es:

<div align="center">

$A=LW$

</div>

### Desarrollo paso a paso

Sustituimos:

<div align="center">

$A=(12.71\,m)(3.46\,m)$

</div>

Primero calculamos sin redondear:

<div align="center">

$A=43.9766\,m^2$

</div>

Contamos cifras significativas:

- $12.71$ tiene 4;
- $3.46$ tiene 3.

Por tanto, el resultado debe tener 3 cifras significativas.

<div align="center">

$43.9766\rightarrow44.0$

</div>

### Resultado

<div align="center">

$\boxed{A=44.0\,m^2}$

</div>

### Interpretacion fisica

Los digitos que muestra una calculadora no representan automaticamente precision experimental.

## Ejercicios del final

### Ejercicio 20

**a)**

<div align="center">

$78.9\pm0.2$

</div>

Tiene:

<div align="center">

$\boxed{3\ cifras\ significativas}$

</div>

**b)**

<div align="center">

$3.788\times10^9$

</div>

Tiene:

<div align="center">

$\boxed{4\ cifras\ significativas}$

</div>

**c)**

<div align="center">

$2.46\times10^{-6}$

</div>

Tiene:

<div align="center">

$\boxed{3\ cifras\ significativas}$

</div>

**d)**

<div align="center">

$0.0053$

</div>

Los ceros iniciales no cuentan:

<div align="center">

$\boxed{2\ cifras\ significativas}$

</div>

### Ejercicio 21 — Año tropical

Datos:

<div align="center">

$365.242199\,dias$

</div>

Convertimos dias a horas:

<div align="center">

$365.242199\,dias \left(\frac{24\,h}{1\,dia}\right)$

</div>

Se cancela dia:

<div align="center">

$=365.242199(24)\,h$

</div>

Convertimos horas a segundos:

<div align="center">

$365.242199(24) \left(\frac{3600\,s}{1\,h}\right)$

</div>

Se cancela hora:

<div align="center">

$=31\,556\,925.9936\,s$

</div>

En notacion cientifica:

<div align="center">

$=3.15569259936\times10^7\,s$

</div>

### Resultado

<div align="center">

$\boxed{t\approx3.15569\times10^7\,s}$

</div>

### Ejercicio 29 — Redondeo de tres cifras

El libro presenta:

<div align="center">

$6.379\,m\rightarrow6.38\,m$

</div>

porque el cuarto digito es $9$.

Tambien:

<div align="center">

$6.374\,m\rightarrow6.37\,m$

</div>

porque el cuarto digito es $4$.

Para un numero terminado en 5, el ejercicio introduce el problema del redondeo y compara las alternativas. La idea importante es que una regla de redondeo debe aplicarse consistentemente.

## Dato curioso

Una medicion de $6.0\,cm$ comunica mas informacion que $6\,cm$: el cero final indica que la medicion fue expresada hasta la decima de centimetro.

## Ideas para recordar

- La calculadora no decide cuanta precision tiene una medicion.
- Multiplicacion/division: usa cifras significativas.
- Suma/resta: usa lugares decimales.
- Conserva los digitos intermedios.
- Redondea al final.
