# Fisica - Resumen y ejercicios

Repositorio personal de estudio basado en el indice del libro proporcionado.

## Objetivo

- Crear un resumen propio de cada apartado.
- Mantener las ecuaciones en LaTeX cuando sea posible.
- Registrar conceptos clave, formulas, ejemplos y ejercicios.
- Resolver ejercicios paso a paso.
- Mantener una estructura sencilla para navegar desde GitHub.

## Estructura

```text
fisica/
parte_1_mecanica/
├── 01_fisica_y_medicion/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 02_movimiento_en_una_dimension/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 03_vectores/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 04_movimiento_en_dos_dimensiones/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 05_las_leyes_del_movimiento/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 06_movimiento_circular_y_otras_aplicaciones_de_las_leyes_de_newton/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 07_energia_de_un_sistema/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 08_conservacion_de_la_energia/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 09_cantidad_de_movimiento_lineal_y_colisiones/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 10_rotacion_de_un_objeto_rigido_en_torno_a_un_eje_fijo/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 11_cantidad_de_movimiento_angular/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 12_equilibrio_estatico_y_elasticidad/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 13_gravitacion_universal/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 14_mecanica_de_fluidos/
│   ├── README.md
│   └── ejercicios/
│       └── ...
parte_2_oscilaciones_y_ondas_mecanicas/
├── 15_movimiento_oscilatorio/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 16_movimiento_ondulatorio/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 17_sobreposicion_y_ondas_estacionarias/
│   ├── README.md
│   └── ejercicios/
│       └── ...
parte_3_termodinamica/
├── 18_temperatura/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 19_primera_ley_de_la_termodinamica/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 20_teoria_cinetica_de_los_gases/
│   ├── README.md
│   └── ejercicios/
│       └── ...
├── 21_maquinas_termicas_entropia_y_segunda_ley_de_la_termodinamica/
│   ├── README.md
│   └── ejercicios/
│       └── ...
apendices/
├── tablas_y_conversiones/
├── repaso_matematico/
├── tabla_periodica/
├── unidades_del_si/
└── ejercicios/
recursos/
├── formulas/
└── glosario/
```

## Partes del libro

| Parte | Contenido |
|---|---|
| Parte 1 | Mecanica, capitulos 1-14 |
| Parte 2 | Oscilaciones y ondas mecanicas, capitulos 15-17 |
| Parte 3 | Termodinamica, capitulos 18-21 |
| Apendices | Tablas, repaso matematico, tabla periodica y unidades SI |

## Convencion para cada capitulo

Cada carpeta de capitulo debe contener un `README.md` con el resumen general y una carpeta `ejercicios/` para las soluciones.

Los apartados pueden guardarse como archivos `.md`, por ejemplo:

```text
01_fisica_y_medicion/
├── README.md
├── 01_estandares_de_longitud_masa_y_tiempo.md
├── 02_modelado_y_representaciones_alternativas.md
├── 03_analisis_dimensional.md
├── 04_conversion_de_unidades.md
├── 05_estimaciones_y_calculos_de_orden_de_magnitud.md
├── 06_cifras_significativas.md
└── ejercicios/
```

## Plantilla recomendada para cada apartado

```markdown
# Titulo del apartado

## Resumen

## Conceptos clave

## Formulas

## Explicacion

## Ejemplo

## Ejercicios

## Notas
```

## Ejercicios

Cada ejercicio resuelto seguira, cuando aplique, esta estructura:

```markdown
# Ejercicio XX

## Problema
## Datos
## Incognitas
## Diagrama
## Ecuaciones
## Desarrollo
## Resultado
## Comprobacion
## Concepto relacionado
```

## Indice de capitulos
### Parte 1 Mecanica
- [01] `01_fisica_y_medicion`
  - 1.1 Estándares de longitud, masa y tiempo
  - 1.2 Modelado y representaciones alternativas
  - 1.3 Análisis dimensional
  - 1.4 Conversión de unidades
  - 1.5 Estimaciones y cálculos de orden de magnitud
  - 1.6 Cifras significativas
- [02] `02_movimiento_en_una_dimension`
  - 2.1 Posición, velocidad y rapidez de una partícula
  - 2.2 Velocidad y rapidez instantáneas
  - 2.3 Modelo de análisis: La partícula bajo velocidad constante
  - 2.4 Propuesta del modelo de análisis para resolver problemas
  - 2.5 Aceleración
  - 2.6 Diagramas de movimiento
  - 2.7 Modelo de análisis: La partícula bajo aceleración constante
  - 2.8 Objetos en caída libre
  - 2.9 Ecuaciones cinemáticas deducidas del cálculo
- [03] `03_vectores`
  - 3.1 Sistemas coordenados
  - 3.2 Cantidades vectoriales y escalares
  - 3.3 Aritmética vectorial básica
  - 3.4 Componentes de un vector y vectores unitarios
- [04] `04_movimiento_en_dos_dimensiones`
  - 4.1 Vectores de posición, velocidad y aceleración
  - 4.2 Movimiento en dos dimensiones con aceleración constante
  - 4.3 Movimiento de proyectil
  - 4.4 Modelo de análisis: Partícula en movimiento circular uniforme
  - 4.5 Aceleraciones tangencial y radial
  - 4.4 Velocidad y aceleración relativas
- [05] `05_las_leyes_del_movimiento`
  - 5.1 Concepto de fuerza
  - 5.2 Primera ley de Newton y marcos inerciales
  - 5.3 Masa
  - 5.4 Segunda ley de Newton
  - 5.5 Fuerza gravitacional y peso
  - 5.6 Tercera ley de Newton
  - 5.7 Modelos de análisis utilizando la segunda ley de Newton
- [06] `06_movimiento_circular_y_otras_aplicaciones_de_las_leyes_de_newton`
  - 6.1 Extensión del modelo de partícula en el movimiento circular uniforme
  - 6.2 Movimiento circular no uniforme
  - 6.3 Movimiento en marcos acelerados
  - 6.4 Movimiento en presencia de fuerzas resistivas
- [07] `07_energia_de_un_sistema`
  - 7.1 Sistemas y entornos
  - 7.2 Trabajo realizado por una fuerza constante
  - 7.3 Producto escalar de dos vectores
  - 7.4 Trabajo realizado por una fuerza variable
  - 7.5 Energía cinética y el teorema trabajo-energía cinética
  - 7.6 Energía potencial de un sistema
  - 7.7 Fuerzas conservativas y no conservativas
  - 7.8 Diagramas de energía y equilibrio de un sistema
  - 7.9 Diagramas de energía y equilibrio de un sistema
- [08] `08_conservacion_de_la_energia`
  - 8.1 Modelo de análisis: Sistema aislado (Energía)
  - 8.2 Modelo de análisis: El sistema aislado (Energía)
  - 8.3 Situaciones que incluyen fricción cinética
  - 8.4 Cambios en energía mecánica para fuerzas no conservativas
  - 8.5 Potencia
- [09] `09_cantidad_de_movimiento_lineal_y_colisiones`
  - 9.1 Cantidad de movimiento lineal
  - 9.2 Modelo de análisis: Sistema aislado (cantidad de movimiento)
  - 9.3 Modelo de análisis: Sistema no aislado (cantidad de movimiento)
  - 9.4 Colisiones en una dimensión
  - 9.5 Colisiones en dos dimensiones
  - 9.6 El centro de masa
  - 9.7 Sistemas de muchas partículas
  - 9.8 Sistemas deformables
  - 9.9 Propulsión de cohetes
- [10] `10_rotacion_de_un_objeto_rigido_en_torno_a_un_eje_fijo`
  - 10.1 Posición, velocidad y aceleración angular
  - 10.2 Análisis de modelo: Objeto rígido bajo aceleración angular constante
  - 10.3 Cantidades angulares y traslacionales
  - 10.4 Momento de torsión
  - 10.5 Análisis de modelo: Objeto rígido bajo un momento de torsión neto
  - 10.6 Cálculo de momentos de inercia
  - 10.7 Energía cinética rotacional
  - 10.8 Consideraciones energéticas en el movimiento rotacional
  - 10.9 Movimiento de rodamiento de un objeto rígido
- [11] `11_cantidad_de_movimiento_angular`
  - 11.1 Producto vectorial y momento de torsión
  - 11.2 Modelo de análisis: sistema no aislado (cantidad de movimiento angular)
  - 11.3 Cantidad de movimiento angular de un objeto rígido rotatorio
  - 11.4 Modelo de análisis: sistema aislado (cantidad de movimiento angular)
  - 11.5 El movimiento de giroscopios y trompos
- [12] `12_equilibrio_estatico_y_elasticidad`
  - 12.1 Modelo de análisis: Objeto rígido en equilibrio
  - 12.2 Más acerca del centro de gravedad
  - 12.3 Ejemplos de objetos rígidos en equilibrio estático
  - 12.4 Propiedades elásticas de los sólidos
- [13] `13_gravitacion_universal`
  - 13.1 Ley de Newton de gravitación universal
  - 13.2 Aceleración en caída libre y fuerza gravitacional
  - 13.3 Modelo de análisis: Partícula en un campo (gravitacional)
  - 13.4 Las leyes de Kepler y el movimiento de los planetas
  - 13.5 Energía potencial gravitacional
  - 13.6 Consideraciones energéticas en el movimiento planetario y de satélites
- [14] `14_mecanica_de_fluidos`
  - 14.1 Presión
  - 14.2 Variación de la presión con la profundidad
  - 14.3 Mediciones de presión
  - 14.4 Fuerzas de flotación y principio de Arquímedes
  - 14.5 Dinámica de fluidos
  - 14.6 Ecuación de Bernoulli
  - 14.7 Flujo de fluidos viscosos en tuberías
  - 14.8 Otras aplicaciones de la dinámica de fluidos

### Parte 2 Oscilaciones Y Ondas Mecanicas
- [15] `15_movimiento_oscilatorio`
  - 15.1 Movimiento de un objeto unido a un resorte
  - 15.2 Partícula en movimiento armónico simple
  - 15.3 Energía del oscilador armónico simple
  - 15.4 Comparación de movimiento armónico simple con movimiento circular uniforme
  - 15.5 El péndulo
  - 15.6 Oscilaciones amortiguadas
  - 15.7 Oscilaciones forzadas
- [16] `16_movimiento_ondulatorio`
  - 16.1 Propagación de una perturbación
  - 16.2 Modelo de análisis: onda viajera
  - 16.3 La rapidez de ondas en cuerdas
  - 16.4 Rapidez de transferencia de energía mediante ondas sinusoidales sobre cuerdas
  - 16.5 La ecuación de onda lineal
  - 16.6 Ondas sonoras
  - 16.7 Rapidez de ondas sonoras
  - 16.8 Intensidad de ondas sonoras
  - 16.9 El efecto Doppler
- [17] `17_sobreposicion_y_ondas_estacionarias`
  - 17.1 Modelo de análisis: Ondas en interferencia
  - 17.2 Ondas estacionarias
  - 17.3 Efectos de frontera: Reflexión y transmisión
  - 17.4 Modelo de análisis: Ondas bajo condiciones de frontera
  - 17.5 Resonancia
  - 17.6 Ondas estacionarias en columnas de aire
  - 17.7 Batimientos: Interferencia en el tiempo
  - 17.8 Patrones de ondas no sinusoidales

### Parte 3 Termodinamica
- [18] `18_temperatura`
  - 18.1 Temperatura y ley cero de la termodinámica
  - 18.2 Termómetros y escala de temperatura Celsius
  - 18.3 Termómetro de gas a volumen constante y escala absoluta de temperatura
  - 18.4 Expansión térmica de sólidos y líquidos
  - 18.5 Descripción macroscópica de un gas ideal
- [19] `19_primera_ley_de_la_termodinamica`
  - 19.1 Calor y energía interna
  - 19.2 Calor específico y calorimetría
  - 19.3 Calor latente
  - 19.4 Trabajo y calor en procesos termodinámicos
  - 19.5 Primera ley de la termodinámica
  - 19.6 Mecanismos de transferencia de energía en procesos térmicos
- [20] `20_teoria_cinetica_de_los_gases`
  - 20.1 Modelo molecular de un gas ideal
  - 20.2 Calor específico molar de un gas ideal
  - 20.3 Equipartición de la energía
  - 20.4 Procesos adiabáticos para un gas ideal
  - 20.5 Distribución de rapideces moleculares
- [21] `21_maquinas_termicas_entropia_y_segunda_ley_de_la_termodinamica`
  - 21.1 Máquinas térmicas y segunda ley de la termodinámica
  - 21.2 Bombas de calor y refrigeradores
  - 21.3 Procesos reversibles e irreversibles
  - 21.4 La máquina de Carnot
  - 21.5 Motores de gasolina y diesel
  - 21.6 Entropía
  - 21.7 Entropía en sistemas termodinámicos
  - 21.8 Entropía y la segunda ley

## Apendices

- `A_tablas`: factores de conversion; simbolos, dimensiones y unidades.
- `B_repaso_matematico`: notacion cientifica, algebra, geometria, trigonometria, series, calculo diferencial, calculo integral y propagacion de incertidumbre.
- `C_tabla_periodica_de_los_elementos`.
- `D_unidades_del_SI`.
- `respuestas_a_examenes_rapidos_y_problemas_con_numeracion_impar`.
- `indice`.

## Nota sobre el indice fuente

Se conserva la numeracion tal como aparece en el indice proporcionado. El indice presenta una posible inconsistencia en el capitulo 4 (aparecen dos apartados numerados 4.4) y dos apartados 7.8 y 7.9 con el mismo titulo. Se revisaran contra el contenido del libro antes de modificar esa numeracion. fileciteturn0file0L34-L43 fileciteturn0file0L61-L73