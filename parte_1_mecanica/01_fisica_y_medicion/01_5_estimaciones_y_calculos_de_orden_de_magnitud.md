# 1.5 Estimaciones y calculos de orden de magnitud

## Resumen

Muchas preguntas de fisica no necesitan una respuesta exacta. El objetivo puede ser determinar aproximadamente el tamaño de una cantidad.

El **orden de magnitud** se expresa como una potencia de diez. Para obtenerlo:

1. escribir el numero en notacion cientifica;
2. identificar el multiplicador entre 1 y 10;
3. compararlo con $\\sqrt{10}\\approx3.162$;
4. si el multiplicador es menor que 3.162, conservar la potencia de diez;
5. si es mayor, aumentar en uno la potencia.

Las estimaciones requieren supuestos razonables. El libro destaca que un buen estimador debe reconocer escalas fisicas y aceptar que el resultado puede ser correcto dentro de un factor aproximado de diez.

## Conceptos clave

- Estimacion.
- Orden de magnitud.
- Notacion cientifica.
- Suposicion razonable.
- Modelo simplificado.
- Calculo de servilleta.
- Factor de diez.

## Formulas importantes

Si:

$$
N=a\\times10^n
$$

con $1\\le a<10$:

- si $a<\\sqrt{10}$, el orden es $10^n$;
- si $a>\\sqrt{10}$, el orden es $10^{n+1}$.

## Ejemplo del libro

### Problema

Estimar el numero de respiraciones realizadas por una persona durante una vida promedio.

### Datos

El libro utiliza aproximadamente:

- vida: $70\\,anos$;
- respiraciones: $10\\,respiraciones/min$;
- un ano: aproximadamente $400\\,dias$;
- un dia: aproximadamente $25\\,h$.

### Que se busca

El orden de magnitud del numero total de respiraciones.

### Principio fisico

Construir una cadena de estimaciones sencillas y multiplicarlas.

### Desarrollo paso a paso

Minutos por ano:

$$
(400\\,d/ano)(25\\,h/d)(60\\,min/h)
\\approx6\\times10^5\\,min/ano
$$

Minutos en 70 anos:

$$
(70\\,anos)(6\\times10^5\\,min/ano)
\\approx4\\times10^7\\,min
$$

Respiraciones:

$$
(10\\,resp/min)(4\\times10^7\\,min)
\\approx4\\times10^8\\,resp
$$

El orden de magnitud es:

$$
\\boxed{10^9\\ respiraciones}
$$

### Resultado

Una persona realiza del orden de mil millones de respiraciones durante una vida.

### Interpretacion fisica

La precision de cada supuesto individual no es importante mientras el objetivo sea determinar la escala general.

## Ejercicios del final

### Ejercicio 17

Estimar el orden de magnitud de la masa de una bañera medio llena de agua y de una bañera medio llena de monedas.

**Parte a: agua**

Supongamos:

$$
V\\sim0.3\\,m^3
$$

y una densidad aproximada del agua:

$$
\\rho\\sim10^3\\,kg/m^3
$$

Entonces:

$$
m\\sim\\rho V
$$

$$
m\\sim(10^3)(0.3)
\\sim3\\times10^2\\,kg
$$

Por tanto:

$$
\\boxed{m\\sim10^2\\,kg}
$$

**Parte b: monedas**

Para monedas apiladas de manera irregular, una estimacion razonable de densidad efectiva puede ser del orden de $10^3\\,kg/m^3$ y un volumen de unos $0.3\\,m^3$:

$$
m\\sim10^3(0.3)
\\sim3\\times10^2\\,kg
$$

De nuevo:

$$
\\boxed{m\\sim10^2\\,kg}
$$

La cifra exacta depende mucho de la geometria y del espacio vacio entre monedas; por eso el objetivo es solamente el orden de magnitud.

### Ejercicio 18

Estimar cuántos afinadores de piano pueden residir en la ciudad de Nueva York.

**Una estimacion posible:**

Supongamos:

- poblacion: $10^7$ personas;
- aproximadamente $2.5$ personas por hogar;
- un piano por cada $10^2$ hogares;
- cada piano requiere aproximadamente una afinacion anual;
- un afinador realiza unas $5\\times10^2$ afinaciones por ano.

Numero de hogares:

$$
\\frac{10^7}{2.5}\\sim4\\times10^6
$$

Pianos:

$$
\\frac{4\\times10^6}{10^2}
\\sim4\\times10^4
$$

Afinadores necesarios:

$$
\\frac{4\\times10^4}{5\\times10^2}
\\sim8\\times10^1
$$

Por tanto:

$$
\\boxed{N\\sim10^2\\ afinadores}
$$

**Nota:** es una estimacion tipo Fermi; el resultado depende de los supuestos elegidos.

### Ejercicio 19

El problema pide demostrar, mediante un calculo de orden de magnitud, que la concentracion de asteroides grandes en el cinturon de asteroides es pequena.

El planteamiento general es:

1. estimar el volumen de la region;
2. usar el numero estimado de asteroides grandes, $\\sim10^9$;
3. calcular una densidad espacial aproximada;
4. comparar el espacio promedio disponible con el tamaño de un asteroide.

Con:

$$
1\\,UA=1.496\\times10^{11}\\,m
$$

la region se extiende aproximadamente entre $2.06$ y $3.27\\,UA$.

El punto fisico importante es que incluso con $10^9$ objetos, la region orbital tiene una escala enorme comparada con el tamaño de asteroides de radio $\\sim100\\,m$.

**Conclusión de orden de magnitud:** la separacion media entre objetos es enorme frente a su tamaño, por lo que la probabilidad geometrica de que una nave encuentre un asteroide grande en su vecindad inmediata es muy pequena.

## Dato curioso

Los calculos de orden de magnitud tambien se conocen como "calculos de servilleta" porque pueden hacerse rapidamente con unas pocas aproximaciones razonables y muy poca aritmetica.

## Ideas para recordar

- No toda pregunta requiere una respuesta exacta.
- Primero identifica las escalas importantes.
- Declara tus supuestos.
- Trabaja con potencias de diez.
- Una estimacion debe ser fisicamente razonable, aunque no sea exacta.
