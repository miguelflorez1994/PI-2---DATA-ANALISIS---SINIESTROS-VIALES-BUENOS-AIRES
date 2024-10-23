<h1 align="center">Proyecto Individual No. 2: Análisis del comportamiento vial para la  prevención de accidentes de tránsito </h1>


## Antecedentes

Los siniestros viales representan una de las principales problemáticas de seguridad pública en Argentina, con aproximadamente 4,000 víctimas fatales cada año. En la Ciudad de Buenos Aires, como principal centro urbano del país, esta realidad se intensifica debido a su alta densidad poblacional y el intenso flujo vehicular que caracteriza a la metrópolis.

![Ciudad de Buenos Aires](https://cdn.pixabay.com/photo/2019/06/03/06/00/argentina-4248156_1280.jpg)

## Contexto

El análisis de datos sobre siniestros viales en Buenos Aires emerge como una herramienta fundamental para comprender patrones, identificar zonas de riesgo y desarrollar estrategias efectivas de prevención. La transformación de datos permite a las autoridades y planificadores urbanos tomar decisiones basadas en evidencia para mejorar la seguridad vial.
Con una tasa de mortalidad por accidentes de tránsito que supera dos a tres veces la probabilidad de fallecimiento por hechos delictivos, resulta imperativo abordar esta problemática desde un enfoque analítico y sistemático. 

![Accidente imágen](https://media.istockphoto.com/id/451333971/es/foto/auto-accidente-con-dos-coches-que-implican.jpg?s=1024x1024&w=is&k=20&c=-cKt-Qj3Wob_nazJtxIwP5YY9pE-d-EF3qF5UPnRtP0=)

## Objetivo

Analizar y descubrir las tendencias significativas en los siniestros viales de CABA, con el fin de generar recomendaciones estratégicas y efectivas que ayuden a disminuir la mortalidad causada por accidentes de tránsito en la ciudad.

## Desarrollo del análisis

El presente análisis busca examinar las variables más significativas que inciden en los siniestros viales, identificar patrones temporales y espaciales, y proponer recomendaciones concretas para reducir la frecuencia y severidad de estos incidentes, contribuyendo así a la construcción de una ciudad más segura para todos sus habitantes.

Se toma para objeto del estudio el repositorio la siguiente base de datos:

[Base de datos siniestros viales  ](https://docs.google.com/spreadsheets/d/1nq00jGIZHQ1RLSET43zKnUsMsoFb-pBg/edit#gid=1625530738)

Se utilizaron 2 datasets para el  análisis: el primero contiene información sobre los accidentes de tránsito ocurridos en la ciudad autónoma de Buenos aires entre los años 2016 y 2021, llamado 'hechos'.

El segundo contiene información relacionada a los accidentes o siniestros mencionados anteriormente pero nos brinda un poco más de información desde el punto de vista de las victimas, dataset llamado 'victimas'.

## Estructura

El proyecto entregado contiene la siguiente  estructura:

### Limpieza de datos o ETL

Se realizan los chequeos de valores nulos, duplicados, corrección de escritura, símbolos, entre otros, se utiliza de guia el diccionario de datos para entender las variables claves de los siniestros viales del estudio.

### Análisis exploratorio de datos (EDA)

Se realizan gráficos de variables más relevantes, en función del tiempo, género, tipo de calle, entre otras.

### Dashboard en Power BI

Se realiza entrega de un Dashboard interactivo que permite identificar elementos  clave de los siniestros viales en la ciudad de Buenos Aires, como la ubicación,  el tipo de accidente, el género de las víctimas, entre otros.


## KPI's

Estos indicadors claves planteados ayudan a entender si las estrategias de mejora en cuando a seguridad vial están teniendo  el impacto esperado, los KPI's propuestos son los siguientes:

- Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en la ciudad de Buenos Aires, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

- Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

- Reducir en un 10% la cantidad de accidentes mortales en intersecciones o cruces  de calles, en CABA, en comparación con el semestre anterior.


## Bibliotecas Utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- warnings

# Conclusiones y recomendaciones

1. **Identificación de zonas de riesgo**: El análisis de datos reveló que las  zonas con mayor concentración de siniestros viales se encuentran en áreas con alta  densidad poblacional y tráfico intenso, como el centro de la ciudad y los accesos  a los principales corredores viales.  Se recomienda implementar medidas de control  de tráfico y seguridad en estas áreas, como la  instalación de cámaras de seguridad,  señalización adecuada y la implementación de  sistemas de control de velocidad.

2. **Reductores de velocidad en zonas de mitad  de cuadra**: Si bien la mayoría de los accidentes se presentan en los cruces, a mitad de las cuadras, es decir, a las alturas de las calles donde la  velocidad de los  vehículos es mayor. Se recomienda la instalación de reductores de  velocidad en las comunas donde se presentan más siniestros para reducir la velocidad de los vehículos y disminuir la   probabilidad de accidentes.

3. **Campañas de concienciación**: Se sugiere la realización de campañas  de concienciación  sobre la importancia de la seguridad vial, dirigidas a los   conductores, peatones y ciclistas, con el fin de cambiar la cultura de  la seguridad  vial y reducir la frecuencia de accidentes.

4. **Implementación de sistemas de control de velocidad**: Se recomienda la  implementación de sistemas de  control de velocidad en las zonas de mayor  riesgo,  como radares y cámaras  de velocidad, para disuadir a los conductores de  exceder  los límites, sobre todo en las avenidas donde se experimentó una mayor cantidad de accidentalidad.

5. **Implementación de sistemas de alerta**: Se recomienda la implementación de  sistemas de  alerta  para los conductores,  como señales de tráfico  inteligentes y   aplicaciones móviles,  para  alertar sobre condiciones de tráfico  peligrosas.

6. **Implementación de programas de educación vial**: Se recomienda la  implementación de   programas de educación vial en las escuelas,  para  educar a los   jóvenes sobre la importancia de la seguridad vial.

# Autor

Miguel Flórez Betancourt
