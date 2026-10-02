# 1.1 Estandares de longitud, masa y tiempo

## Resumen

La mecanica utiliza tres cantidades fundamentales: longitud, masa y tiempo. En el Sistema Internacional (SI) sus unidades son metro (m), kilogramo (kg) y segundo (s).

Una medicion necesita un estandar que permita comparar resultados. El libro presenta la evolucion historica de los estandares de longitud, masa y tiempo y destaca la necesidad de contar con referencias reproducibles y precisas.

La densidad es una cantidad derivada y se define como masa por unidad de volumen:

$\rho=\frac{m}{V}$

Para un objeto esferico:

$V=\frac{4}{3}\pi r^3$

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

$\rho=\frac{m}{V}$

**Que significa:** indica cuanta masa existe por cada unidad de volumen.

Si conocemos la masa y queremos el volumen:

$V=\frac{m}{\rho}$

Si conocemos densidad y volumen y queremos masa:

$m=\rho V$

### Volumen de una esfera

$V=\frac{4}{3}\pi r^3$

El radio debe estar expresado en las unidades de longitud deseadas antes de elevarlo al cubo.

### Densidad de una esfera

Partimos de:

$\rho=\frac{m}{V}$

Sustituimos el volumen de una esfera:

$\rho=\frac{m}{\frac{4}{3}\pi r^3}$

Dividir entre una fraccion equivale a multiplicar por su reciproco:

$\rho=m\left(\frac{3}{4\pi r^3}\right)$

Por tanto:

$\boxed{\rho=\frac{3m}{4\pi r^3}}$

**Este paso es importante:** el factor $3/4$ no aparece de la nada; proviene de invertir la fraccion $4/3$ al dividir entre el volumen.

## Ejemplo del libro

### Problema

Encontrar la altura de un arbol que no puede medirse directamente.

### Datos

$d=50.0\,m$

$\theta=25.0^\circ$

### Que se busca

La altura $h$ del arbol.

### Principio fisico

El arbol y la distancia al observador se representan como un triangulo rectangulo.

$\tan\theta=\frac{\text{cateto opuesto}}{\text{cateto adyacente}}$

En este problema:

$\tan\theta=\frac{h}{d}$

### Desarrollo paso a paso

Partimos de:

$\tan\theta=\frac{h}{d}$

Multiplicamos ambos lados por $d$:

$d\tan\theta=h$

Por tanto:

$h=d\tan\theta$

Sustituimos:

$h=(50.0\,m)\tan(25.0^\circ)$

Calculando:

$\tan(25.0^\circ)\approx0.4663$

Entonces:

$h=(50.0\,m)(0.4663)$

$h\approx23.3\,m$

### Resultado

$\boxed{h=23.3\,m}$

### Interpretacion fisica

La altura se obtuvo indirectamente mediante una distancia facilmente medible y un angulo.

## Ejercicios del final

### Ejercicio 1 — Densidad promedio de la Tierra

El problema pide calcular la densidad promedio de la Tierra utilizando su masa y radio.

**Datos del libro:**

$M=5.98\times10^{24}\,kg$

$R=6.37\times10^6\,m$

### Paso 1: volumen de la Tierra

Modelamos la Tierra como una esfera:

$V=\frac{4}{3}\pi R^3$

Sustituimos el radio:

$V=\frac{4}{3}\pi(6.37\times10^6\,m)^3$

Primero elevamos el radio al cubo:

$(6.37\times10^6)^3 = 6.37^3\times10^{18}$

$6.37^3\approx258.5$

Por tanto:

$R^3\approx2.585\times10^{20}\,m^3$

Ahora:

$V=\frac{4}{3}\pi(2.585\times10^{20}\,m^3)$

$V\approx1.083\times10^{21}\,m^3$

### Paso 2: densidad

La definicion es:

$\rho=\frac{M}{V}$

Sustituimos:

$\rho= \frac{5.98\times10^{24}\,kg} {1.083\times10^{21}\,m^3}$

Separamos coeficientes y potencias:

$\rho= \left(\frac{5.98}{1.083}\right) \times10^{24-21} \frac{kg}{m^3}$

$\rho\approx5.52\times10^3\,kg/m^3$

### Comprobacion mediante despeje directo

Tambien podemos sustituir directamente el volumen en la ecuacion de densidad:

$\rho= \frac{M} {\frac{4}{3}\pi R^3}$

Ahora se muestra explicitamente el paso que no debe omitirse:

$\rho= M\left(\frac{3}{4\pi R^3}\right)$

y finalmente:

$\boxed{\rho=\frac{3M}{4\pi R^3}}$

Sustituyendo:

$\rho= \frac{3(5.98\times10^{24}\,kg)} {4\pi(6.37\times10^6\,m)^3}$

$\boxed{\rho\approx5.52\times10^3\,kg/m^3}$

### Interpretacion fisica

La densidad promedio de la Tierra es aproximadamente $5.5\times10^3\,kg/m^3$. Este valor debe compararse con materiales de la superficie; la Tierra no tiene una densidad uniforme.

### Ejercicio 2 — Densidad de un proton

**Datos:**

$d=2.4\,fm$

$m=1.67\times10^{-27}\,kg$

Como:

$1\,fm=10^{-15}\,m$

entonces:

$d=(2.4)(10^{-15})\,m$

$d=2.4\times10^{-15}\,m$

El radio es la mitad del diametro:

$r=\frac{d}{2}$

$r=\frac{2.4\times10^{-15}\,m}{2}$

$r=1.2\times10^{-15}\,m$

Volumen:

$V=\frac{4}{3}\pi r^3$

$V=\frac{4}{3}\pi(1.2\times10^{-15}\,m)^3$

$V\approx7.24\times10^{-45}\,m^3$

Densidad:

$\rho=\frac{m}{V}$

$\rho= \frac{1.67\times10^{-27}\,kg} {7.24\times10^{-45}\,m^3}$

$\boxed{\rho\approx2.31\times10^{17}\,kg/m^3}$

### Ejercicio 3 — Dos esferas de la misma roca

Una esfera tiene radio $r_1=4.50\,cm$ y la segunda tiene una masa cinco veces mayor.

Como ambas son del mismo material:

$\rho_1=\rho_2$

Y:

$m=\rho V$

Entonces:

$m=\rho\frac{4}{3}\pi r^3$

Por tanto:

$m\propto r^3$

Si:

$m_2=5m_1$

entonces:

$\frac{m_2}{m_1}=5 = \frac{r_2^3}{r_1^3}$

Despejamos:

$r_2^3=5r_1^3$

Aplicamos raiz cubica:

$r_2=\sqrt[3]{5r_1^3}$

$r_2=r_1\sqrt[3]{5}$

Sustituimos:

$r_2=(4.50\,cm)\sqrt[3]{5}$

$\boxed{r_2\approx7.69\,cm}$

## Dato curioso

La definicion moderna del metro utiliza la velocidad de la luz en el vacio, mientras que el segundo se relaciona con la frecuencia de la radiacion del cesio-133. Los estandares modernos buscan ser reproducibles y extremadamente precisos.

## Ideas para recordar

- No confundas masa con peso.
- El SI usa m, kg y s como unidades fundamentales de mecanica.
- La densidad es masa dividida entre volumen.
- Si el objeto es una esfera, primero calcula su volumen.
- Si una fraccion aparece en el denominador, muestra explicitamente su inversion al despejar.
