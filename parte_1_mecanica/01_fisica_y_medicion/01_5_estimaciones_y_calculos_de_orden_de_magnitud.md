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

$N=a\times10^n$

con:

$1\le a<10$

entonces:

- si $a<3.162$, el orden es $10^n$;
- si $a>3.162$, el orden es $10^{n+1}$.

## Ejemplo del libro

### Problema

Estimar el numero de respiraciones realizadas durante una vida humana promedio.

### Datos aproximados

$70\,anos$

$10\,respiraciones/min$

Para simplificar:

$1\,ano\approx400\,dias$

$1\,dia\approx25\,h$

$1\,h=60\,min$

### Que se busca

El orden de magnitud del numero total de respiraciones.

### Principio fisico

Construir la estimacion por factores.

### Desarrollo paso a paso

Minutos por año:

$1\,ano \left(\frac{400\,dias}{1\,ano}\right) \left(\frac{25\,h}{1\,dia}\right) \left(\frac{60\,min}{1\,h}\right)$

Se cancelan las unidades:

$=400(25)(60)\,min$

$=600000\,min$

$\approx6\times10^5\,min/ano$

Minutos durante 70 años:

$(70\,anos) \left(6\times10^5\,\frac{min}{ano}\right)$

$=4.2\times10^7\,min$

Respiraciones:

$(10\,resp/min)(4.2\times10^7\,min)$

$=4.2\times10^8\,resp$

Como orden de magnitud:

$4.2\times10^8$

esta mas cerca de $10^9$ que de $10^8$ porque:

$4.2>3.162$

Por tanto:

$\boxed{N\sim10^9\,respiraciones}$

### Resultado

Una persona realiza del orden de mil millones de respiraciones durante su vida.

### Interpretacion fisica

No interesa conocer el numero exacto. Interesa identificar correctamente la escala.

## Ejercicios del final

### Ejercicio 17 — Masa de una bañera

**a) Agua**

Estimamos:

$V\sim0.3\,m^3$

y:

$\rho_{agua}\sim10^3\,kg/m^3$

Usamos:

$m=\rho V$

Sustituimos:

$m\sim(10^3\,kg/m^3)(0.3\,m^3)$

Se cancela $m^3$:

$m\sim3\times10^2\,kg$

Por tanto:

$\boxed{m\sim10^2\,kg}$

**b) Monedas**

El problema es de estimacion. Podemos aproximar una densidad efectiva del orden de $10^3\,kg/m^3$ y un volumen similar:

$m\sim(10^3)(0.3)\,kg$

$m\sim3\times10^2\,kg$

$\boxed{m\sim10^2\,kg}$

El valor depende de cuanto espacio vacio quede entre monedas.

### Ejercicio 18 — Afinadores de piano

Supongamos:

$N_{personas}\sim10^7$

y:

$2.5\,personas/hogar$

Hogares:

$N_{hogares} = \frac{10^7\,personas} {2.5\,personas/hogar}$

$N_{hogares}\sim4\times10^6$

Si aproximadamente uno de cada $10^2$ hogares tiene piano:

$N_{pianos} \sim \frac{4\times10^6}{10^2}$

$N_{pianos}\sim4\times10^4$

Si un afinador realiza del orden de $5\times10^2$ afinaciones por año:

$N_{afinadores} \sim \frac{4\times10^4} {5\times10^2}$

$N_{afinadores}\sim8\times10^1$

Por orden de magnitud:

$\boxed{N\sim10^2}$

### Ejercicio 19 — Cinturon de asteroides

El problema proporciona:

$N\sim10^9$

asteroides de radio de aproximadamente:

$r\sim100\,m$

y una region entre:

$2.06\,UA \quad\text{y}\quad 3.27\,UA$

con:

$1\,UA=1.496\times10^{11}\,m$

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
