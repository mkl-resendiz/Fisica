# 1.1 Estandares de longitud, masa y tiempo

## Resumen

La mecanica utiliza tres cantidades fundamentales: longitud, masa y tiempo. En el Sistema Internacional (SI) sus unidades son metro (m), kilogramo (kg) y segundo (s).

Una medicion necesita un estandar que permita comparar resultados. El libro presenta la evolucion historica de los estandares de longitud, masa y tiempo y destaca la necesidad de contar con referencias reproducibles y precisas.

La densidad es una cantidad derivada y se define como masa por unidad de volumen:

<div align="center">

$\rho=\frac{m}{V}$

</div>

Para un objeto esferico:

<div align="center">

$V=\frac{4}{3}\pi r^3$

</div>

Por tanto, si conocemos la masa y el radio podemos calcular su densidad.

## Conceptos clave

- Cantidades fundamentales.
- Unidades del SI.
- Metro, kilogramo y segundo.
- Tiempo e intervalo de tiempo.
- Cantidades derivadas.
- Densidad.
- Orden de magnitud y valores razonables.

## Formulas importantes

### Densidad

<div align="center">

$\rho=\frac{m}{V}$

</div>

**Que significa:** indica cuanta masa existe por cada unidad de volumen.

Si conocemos la masa y queremos el volumen:

<div align="center">

$V=\frac{m}{\rho}$

</div>

Si conocemos densidad y volumen y queremos masa:

<div align="center">

$m=\rho V$

</div>

### Volumen de una esfera

<div align="center">

$V=\frac{4}{3}\pi r^3$

</div>

El radio debe estar expresado en las unidades de longitud deseadas antes de elevarlo al cubo.

### Densidad de una esfera

Partimos de:

<div align="center">

$\rho=\frac{m}{V}$

</div>

Sustituimos el volumen de una esfera:

<div align="center">

$\rho=\frac{m}{\frac{4}{3}\pi r^3}$

</div>

Dividir entre una fraccion equivale a multiplicar por su reciproco:

<div align="center">

$\rho=m\left(\frac{3}{4\pi r^3}\right)$

</div>

Por tanto:

<div align="center">

$\boxed{\rho=\frac{3m}{4\pi r^3}}$

</div>

**Este paso es importante:** el factor $3/4$ no aparece de la nada; proviene de invertir la fraccion $4/3$ al dividir entre el volumen.

## Ejemplo del libro

### Problema

Encontrar la altura de un arbol que no puede medirse directamente.

### Datos

<div align="center">

$d=50.0\,m$

</div>

<div align="center">

$\theta=25.0^\circ$

</div>

### Que se busca

La altura $h$ del arbol.

### Principio fisico

El arbol y la distancia al observador se representan como un triangulo rectangulo.

<div align="center">

$\tan\theta=\frac{\text{cateto opuesto}}{\text{cateto adyacente}}$

</div>

En este problema:

<div align="center">

$\tan\theta=\frac{h}{d}$

</div>

### Desarrollo paso a paso

Partimos de:

<div align="center">

$\tan\theta=\frac{h}{d}$

</div>

Multiplicamos ambos lados por $d$:

<div align="center">

$d\tan\theta=h$

</div>

Por tanto:

<div align="center">

$h=d\tan\theta$

</div>

Sustituimos:

<div align="center">

$h=(50.0\,m)\tan(25.0^\circ)$

</div>

Calculando:

<div align="center">

$\tan(25.0^\circ)\approx0.4663$

</div>

Entonces:

<div align="center">

$h=(50.0\,m)(0.4663)$

</div>

<div align="center">

$h\approx23.3\,m$

</div>

### Resultado

<div align="center">

$\boxed{h=23.3\,m}$

</div>

### Interpretacion fisica

La altura se obtuvo indirectamente mediante una distancia facilmente medible y un angulo.

## Ejercicios del final

### Ejercicio 1 — Densidad promedio de la Tierra

El problema pide calcular la densidad promedio de la Tierra utilizando su masa y radio.

**Datos del libro:**

<div align="center">

$M=5.98\times10^{24}\,kg$

</div>

<div align="center">

$R=6.37\times10^6\,m$

</div>

### Paso 1: volumen de la Tierra

Modelamos la Tierra como una esfera:

<div align="center">

$V=\frac{4}{3}\pi R^3$

</div>

Sustituimos el radio:

<div align="center">

$V=\frac{4}{3}\pi(6.37\times10^6\,m)^3$

</div>

Primero elevamos el radio al cubo:

<div align="center">

$(6.37\times10^6)^3 = 6.37^3\times10^{18}$

</div>

<div align="center">

$6.37^3\approx258.5$

</div>

Por tanto:

<div align="center">

$R^3\approx2.585\times10^{20}\,m^3$

</div>

Ahora:

<div align="center">

$V=\frac{4}{3}\pi(2.585\times10^{20}\,m^3)$

</div>

<div align="center">

$V\approx1.083\times10^{21}\,m^3$

</div>

### Paso 2: densidad

La definicion es:

<div align="center">

$\rho=\frac{M}{V}$

</div>

Sustituimos:

<div align="center">

$\rho= \frac{5.98\times10^{24}\,kg} {1.083\times10^{21}\,m^3}$

</div>

Separamos coeficientes y potencias:

<div align="center">

$\rho= \left(\frac{5.98}{1.083}\right) \times10^{24-21} \frac{kg}{m^3}$

</div>

<div align="center">

$\rho\approx5.52\times10^3\,kg/m^3$

</div>

### Comprobacion mediante despeje directo

Tambien podemos sustituir directamente el volumen en la ecuacion de densidad:

<div align="center">

$\rho= \frac{M} {\frac{4}{3}\pi R^3}$

</div>

Ahora se muestra explicitamente el paso que no debe omitirse:

<div align="center">

$\rho= M\left(\frac{3}{4\pi R^3}\right)$

</div>

y finalmente:

<div align="center">

$\boxed{\rho=\frac{3M}{4\pi R^3}}$

</div>

Sustituyendo:

<div align="center">

$\rho= \frac{3(5.98\times10^{24}\,kg)} {4\pi(6.37\times10^6\,m)^3}$

</div>

<div align="center">

$\boxed{\rho\approx5.52\times10^3\,kg/m^3}$

</div>

### Interpretacion fisica

La densidad promedio de la Tierra es aproximadamente $5.5\times10^3\,kg/m^3$. Este valor debe compararse con materiales de la superficie; la Tierra no tiene una densidad uniforme.

### Ejercicio 2 — Densidad de un proton

**Datos:**

<div align="center">

$d=2.4\,fm$

</div>

<div align="center">

$m=1.67\times10^{-27}\,kg$

</div>

Como:

<div align="center">

$1\,fm=10^{-15}\,m$

</div>

entonces:

<div align="center">

$d=(2.4)(10^{-15})\,m$

</div>

<div align="center">

$d=2.4\times10^{-15}\,m$

</div>

El radio es la mitad del diametro:

<div align="center">

$r=\frac{d}{2}$

</div>

<div align="center">

$r=\frac{2.4\times10^{-15}\,m}{2}$

</div>

<div align="center">

$r=1.2\times10^{-15}\,m$

</div>

Volumen:

<div align="center">

$V=\frac{4}{3}\pi r^3$

</div>

<div align="center">

$V=\frac{4}{3}\pi(1.2\times10^{-15}\,m)^3$

</div>

<div align="center">

$V\approx7.24\times10^{-45}\,m^3$

</div>

Densidad:

<div align="center">

$\rho=\frac{m}{V}$

</div>

<div align="center">

$\rho= \frac{1.67\times10^{-27}\,kg} {7.24\times10^{-45}\,m^3}$

</div>

<div align="center">

$\boxed{\rho\approx2.31\times10^{17}\,kg/m^3}$

</div>

### Ejercicio 3 — Dos esferas de la misma roca

Una esfera tiene radio $r_1=4.50\,cm$ y la segunda tiene una masa cinco veces mayor.

Como ambas son del mismo material:

<div align="center">

$\rho_1=\rho_2$

</div>

Y:

<div align="center">

$m=\rho V$

</div>

Entonces:

<div align="center">

$m=\rho\frac{4}{3}\pi r^3$

</div>

Por tanto:

<div align="center">

$m\propto r^3$

</div>

Si:

<div align="center">

$m_2=5m_1$

</div>

entonces:

<div align="center">

$\frac{m_2}{m_1}=5 = \frac{r_2^3}{r_1^3}$

</div>

Despejamos:

<div align="center">

$r_2^3=5r_1^3$

</div>

Aplicamos raiz cubica:

<div align="center">

$r_2=\sqrt[3]{5r_1^3}$

</div>

<div align="center">

$r_2=r_1\sqrt[3]{5}$

</div>

Sustituimos:

<div align="center">

$r_2=(4.50\,cm)\sqrt[3]{5}$

</div>

<div align="center">

$\boxed{r_2\approx7.69\,cm}$

</div>

## Dato curioso

La definicion moderna del metro utiliza la velocidad de la luz en el vacio, mientras que el segundo se relaciona con la frecuencia de la radiacion del cesio-133. Los estandares modernos buscan ser reproducibles y extremadamente precisos.

## Ideas para recordar

- No confundas masa con peso.
- El SI usa m, kg y s como unidades fundamentales de mecanica.
- La densidad es masa dividida entre volumen.
- Si el objeto es una esfera, primero calcula su volumen.
- Si una fraccion aparece en el denominador, muestra explicitamente su inversion al despejar.
