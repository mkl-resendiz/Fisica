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

$A=LW$

### Area de un circulo

$A=\pi r^2$

Para multiplicar:

$\text{cifras significativas del resultado} = \text{menor numero de cifras significativas de los datos}$

Para sumar o restar:

$\text{lugares decimales del resultado} = \text{menor numero de lugares decimales de los datos}$

## Ejemplo del libro

### Problema

Una habitacion mide:

$L=12.71\,m$

$W=3.46\,m$

Encontrar el area.

### Que se busca

$A=?$

### Principio fisico

El area de un rectangulo es:

$A=LW$

### Desarrollo paso a paso

Sustituimos:

$A=(12.71\,m)(3.46\,m)$

Primero calculamos sin redondear:

$A=43.9766\,m^2$

Contamos cifras significativas:

- $12.71$ tiene 4;
- $3.46$ tiene 3.

Por tanto, el resultado debe tener 3 cifras significativas.

$43.9766\rightarrow44.0$

### Resultado

$\boxed{A=44.0\,m^2}$

### Interpretacion fisica

Los digitos que muestra una calculadora no representan automaticamente precision experimental.

## Ejercicios del final

### Ejercicio 20

**a)**

$78.9\pm0.2$

Tiene:

$\boxed{3\ cifras\ significativas}$

**b)**

$3.788\times10^9$

Tiene:

$\boxed{4\ cifras\ significativas}$

**c)**

$2.46\times10^{-6}$

Tiene:

$\boxed{3\ cifras\ significativas}$

**d)**

$0.0053$

Los ceros iniciales no cuentan:

$\boxed{2\ cifras\ significativas}$

### Ejercicio 21 — Año tropical

Datos:

$365.242199\,dias$

Convertimos dias a horas:

$365.242199\,dias \left(\frac{24\,h}{1\,dia}\right)$

Se cancela dia:

$=365.242199(24)\,h$

Convertimos horas a segundos:

$365.242199(24) \left(\frac{3600\,s}{1\,h}\right)$

Se cancela hora:

$=31\,556\,925.9936\,s$

En notacion cientifica:

$=3.15569259936\times10^7\,s$

### Resultado

$\boxed{t\approx3.15569\times10^7\,s}$

### Ejercicio 29 — Redondeo de tres cifras

El libro presenta:

$6.379\,m\rightarrow6.38\,m$

porque el cuarto digito es $9$.

Tambien:

$6.374\,m\rightarrow6.37\,m$

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
