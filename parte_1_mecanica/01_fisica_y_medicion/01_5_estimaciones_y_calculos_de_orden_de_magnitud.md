# 1.5 Estimaciones y calculos de orden de magnitud

## Resumen

Una estimacion busca una respuesta razonable sin necesidad de conocer todos los datos con precision. El orden de magnitud expresa la escala aproximada mediante una potencia de diez.

El libro propone:

1. escribir el numero en notacion cientifica;
2. comparar el multiplicador con $3.162=\sqrt{10}$;
3. elegir la potencia de diez mas cercana.

Las estimaciones suelen ser confiables dentro de un factor aproximado de diez.

## Conceptos clave

- Estimacion.
- Orden de magnitud.
- Notacion cientifica.
- Supuestos razonables.
- Calculo de servilleta.

## Formulas importantes

Si:

<div align="center">

$N=a\times10^n$

</div>

con:

<div align="center">

$1\le a<10$

</div>

entonces:

- si $a<3.162$, el orden es $10^n$;
- si $a>3.162$, el orden es $10^{n+1}$.

## Ejemplo del libro

### Problema

Estimar el numero de respiraciones realizadas durante una vida humana promedio.

### Datos aproximados

<div align="center">

$70\,anos$

</div>

<div align="center">

$10\,respiraciones/min$

</div>

Para simplificar:

<div align="center">

$1\,ano\approx400\,dias$

</div>

<div align="center">

$1\,dia\approx25\,h$

</div>

<div align="center">

$1\,h=60\,min$

</div>

### Que se busca

El orden de magnitud del numero total de respiraciones.

### Principio fisico

Construir la estimacion por factores.

### Desarrollo paso a paso

Minutos por año:

<div align="center">

$1\,ano \left(\frac{400\,dias}{1\,ano}\right) \left(\frac{25\,h}{1\,dia}\right) \left(\frac{60\,min}{1\,h}\right)$

</div>

Se cancelan las unidades:

<div align="center">

$=400(25)(60)\,min$

</div>

<div align="center">

$=600000\,min$

</div>

<div align="center">

$\approx6\times10^5\,min/ano$

</div>

Minutos durante 70 años:

<div align="center">

$(70\,anos) \left(6\times10^5\,\frac{min}{ano}\right)$

</div>

<div align="center">

$=4.2\times10^7\,min$

</div>

Respiraciones:

<div align="center">

$(10\,resp/min)(4.2\times10^7\,min)$

</div>

<div align="center">

$=4.2\times10^8\,resp$

</div>

Como orden de magnitud:

<div align="center">

$4.2\times10^8$

</div>

esta mas cerca de $10^9$ que de $10^8$ porque:

<div align="center">

$4.2>3.162$

</div>

Por tanto:

<div align="center">

$\boxed{N\sim10^9\,respiraciones}$

</div>

### Resultado

Una persona realiza del orden de mil millones de respiraciones durante su vida.

### Interpretacion fisica

No interesa conocer el numero exacto. Interesa identificar correctamente la escala.

## Ejercicios del final

### Ejercicio 17 — Masa de una bañera

**a) Agua**

Estimamos:

<div align="center">

$V\sim0.3\,m^3$

</div>

y:

<div align="center">

$\rho_{agua}\sim10^3\,kg/m^3$

</div>

Usamos:

<div align="center">

$m=\rho V$

</div>

Sustituimos:

<div align="center">

$m\sim(10^3\,kg/m^3)(0.3\,m^3)$

</div>

Se cancela $m^3$:

<div align="center">

$m\sim3\times10^2\,kg$

</div>

Por tanto:

<div align="center">

$\boxed{m\sim10^2\,kg}$

</div>

**b) Monedas**

El problema es de estimacion. Podemos aproximar una densidad efectiva del orden de $10^3\,kg/m^3$ y un volumen similar:

<div align="center">

$m\sim(10^3)(0.3)\,kg$

</div>

<div align="center">

$m\sim3\times10^2\,kg$

</div>

<div align="center">

$\boxed{m\sim10^2\,kg}$

</div>

El valor depende de cuanto espacio vacio quede entre monedas.

### Ejercicio 18 — Afinadores de piano

Supongamos:

<div align="center">

$N_{personas}\sim10^7$

</div>

y:

<div align="center">

$2.5\,personas/hogar$

</div>

Hogares:

<div align="center">

$N_{hogares} = \frac{10^7\,personas} {2.5\,personas/hogar}$

</div>

<div align="center">

$N_{hogares}\sim4\times10^6$

</div>

Si aproximadamente uno de cada $10^2$ hogares tiene piano:

<div align="center">

$N_{pianos} \sim \frac{4\times10^6}{10^2}$

</div>

<div align="center">

$N_{pianos}\sim4\times10^4$

</div>

Si un afinador realiza del orden de $5\times10^2$ afinaciones por año:

<div align="center">

$N_{afinadores} \sim \frac{4\times10^4} {5\times10^2}$

</div>

<div align="center">

$N_{afinadores}\sim8\times10^1$

</div>

Por orden de magnitud:

<div align="center">

$\boxed{N\sim10^2}$

</div>

### Ejercicio 19 — Cinturon de asteroides

El problema proporciona:

<div align="center">

$N\sim10^9$

</div>

asteroides de radio de aproximadamente:

<div align="center">

$r\sim100\,m$

</div>

y una region entre:

<div align="center">

$2.06\,UA \quad\text{y}\quad 3.27\,UA$

</div>

con:

<div align="center">

$1\,UA=1.496\times10^{11}\,m$

</div>

El planteamiento consiste en estimar el volumen de la region y compararlo con el volumen ocupado por los asteroides.

La idea central es que, aunque $10^9$ parece un numero enorme, el espacio disponible en una region astronomica es mucho mayor que el volumen combinado de los asteroides.

**Conclusion de orden de magnitud:** la concentracion espacial de asteroides grandes es muy baja.

## Dato curioso

Los problemas de estimacion se conocen informalmente como "calculos de servilleta": pueden resolverse con pocos supuestos y operaciones sencillas.

## Ideas para recordar

- Estimar no significa adivinar.
- Declara tus supuestos.
- Usa numeros sencillos pero razonables.
- Trabaja con potencias de diez.
- No necesitas precision de calculadora para conocer una escala.
