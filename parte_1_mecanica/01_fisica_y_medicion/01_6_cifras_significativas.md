# 1.6 Cifras significativas

## Resumen

Las mediciones experimentales tienen incertidumbre. Las **cifras significativas** comunican cuanta precision esta contenida en una medicion.

El libro utiliza como ejemplo una medicion de radio de $6.0\\,cm$ con incertidumbre de $\\pm0.1\\,cm$. El ultimo digito comunicado forma parte de la precision de la medicion.

Los ceros pueden ser significativos o no. Para evitar ambiguedades, la notacion cientifica es especialmente util.

Reglas principales:

- en multiplicacion y division, el resultado conserva el numero de cifras significativas de la cantidad con menos cifras significativas;
- en suma y resta, el resultado conserva el menor numero de lugares decimales;
- no conviene redondear en pasos intermedios;
- el redondeo se realiza al final.

## Conceptos clave

- Incertidumbre experimental.
- Cifras significativas.
- Lugar decimal.
- Notacion cientifica.
- Redondeo.
- Precision de una medicion.
- Error de redondeo.

## Formulas importantes

### Area de un circulo

$$
A=\\pi r^2
$$

### Regla para multiplicacion y division

El resultado debe conservar tantas cifras significativas como la cantidad con menos cifras significativas.

### Regla para suma y resta

El resultado debe conservar tantos lugares decimales como el termino con menos lugares decimales.

## Ejemplo del libro

### Problema

Una habitacion mide $12.71\\,m$ de largo y $3.46\\,m$ de ancho. Encontrar el area de la alfombra.

### Datos

$$
L=12.71\\,m
$$

$$
W=3.46\\,m
$$

### Que se busca

El area.

### Principio fisico

Para un rectangulo:

$$
A=LW
$$

### Desarrollo paso a paso

Calculadora:

$$
A=(12.71)(3.46)=43.9766\\,m^2
$$

Ahora contamos cifras significativas:

- $12.71$ tiene 4;
- $3.46$ tiene 3.

La respuesta debe tener 3 cifras significativas:

$$
43.9766\\rightarrow44.0
$$

### Resultado

$$
\\boxed{A=44.0\\,m^2}
$$

### Interpretacion fisica

Los digitos adicionales que aparecen en la calculadora no representan precision real adicional. La respuesta debe reflejar la precision de las mediciones de entrada.

## Ejercicios del final

### Ejercicio 20

Determinar las cifras significativas de:

**a) $78.9\\pm0.2$**

La medicion esta expresada hasta las decimas:

$$
\\boxed{3\\ cifras\\ significativas}
$$

**b) $3.788\\times10^9$**

$$
\\boxed{4\\ cifras\\ significativas}
$$

**c) $2.46\\times10^{-6}$**

$$
\\boxed{3\\ cifras\\ significativas}
$$

**d) $0.0053$**

Los ceros iniciales solo colocan el punto decimal:

$$
\\boxed{2\\ cifras\\ significativas}
$$

### Ejercicio 21

Un ano tropical contiene $365.242199$ dias. Encontrar el numero de segundos.

Primero:

$$
1\\,dia=24\\,h
$$

$$
1\\,h=3600\\,s
$$

Por tanto:

$$
t=(365.242199)(24)(3600)
$$

$$
t=31\\,556\\,925.9936\\,s
$$

La precision del dato inicial permite reportar aproximadamente:

$$
\\boxed{3.15569\\times10^7\\,s}
$$

### Ejercicio 29

El problema analiza el redondeo cuando se requieren tres cifras significativas, incluyendo el caso en que el siguiente digito es exactamente 5.

Ejemplos del libro:

$$
6.379\\,m\\rightarrow6.38\\,m
$$

porque el siguiente digito es mayor que 5.

Tambien:

$$
6.374\\,m\\rightarrow6.37\\,m
$$

porque el siguiente digito es menor que 5.

Para:

$$
6.375\\,m
$$

el libro presenta la regla de redondear el ultimo digito retenido hacia el numero par mas cercano para evitar una acumulacion sistematica de errores.

Con tres cifras significativas:

$$
\\boxed{6.375\\,m\\rightarrow6.38\\,m}
$$

## Dato curioso

La cantidad de cifras significativas de una respuesta no depende solamente de la calculadora. Una calculadora puede mostrar muchos digitos, pero esos digitos adicionales pueden no estar respaldados por la precision de las mediciones originales.

## Ideas para recordar

- Las cifras significativas comunican precision.
- Los ceros iniciales no son significativos.
- Los ceros finales pueden ser significativos y conviene usar notacion cientifica para evitar ambiguedad.
- Multiplicacion/division: manda el menor numero de cifras significativas.
- Suma/resta: manda el menor numero de lugares decimales.
- Conserva todos los digitos durante el calculo y redondea al final.
