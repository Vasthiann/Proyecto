# Modelo de Predicción del Índice de Calidad del Aire: [PM10]

## Introducción
La predicción del índice de calidad del aire es esencial para proteger la salud pública y gestionar el medio ambiente, ya que permite comprender la presencia de contaminantes en la atmósfera, como partículas suspendidas y contaminantes químicos. Este informe se centra principalmente en los niveles de PM10 en California, conocido como el "estado dorado", ubicado en Estados Unidos, durante los años 2022 y 2023. California enfrenta desafíos ambientales como el cambio climático, los incendios forestales y la necesidad de gestionar la calidad del aire, dado el aumento en la frecuencia de incendios y las olas de calor en las últimas décadas.(1)

Toda la información fue obtenida de la base de datos de la Agencia de Protección Ambiental de los Estados Unidos (EPA). Se trabajó con los datos de calidad del aire recopilados en monitores al aire libre a lo largo de Estados Unidos, en particular para el contaminante PM10 durante los años 2022 y 2023, con mediciones promedio durante 24 horas al día.

Las partículas PM10 son una mezcla de partículas sólidas y líquidas de menos de 10 micrómetros de diámetro que se encuentran suspendidas en el aire. Provienen de fuentes como el tráfico vehicular, la construcción, la quema de combustibles fósiles y los incendios forestales. Debido a su tamaño, estas partículas pueden ser inhaladas y llegar hasta los pulmones, lo que representa un riesgo significativo para la salud respiratoria y cardiovascular, especialmente en personas vulnerables como niños, ancianos y personas con enfermedades pulmonares.(3_
California, por su geografía y clima, es particularmente susceptible a altos niveles de PM10, especialmente durante los incendios forestales que generan grandes cantidades de humo y partículas en suspensión. Los niveles de PM10 en 2022 y 2023 reflejan la importancia de implementar políticas de mitigación y prevención para reducir la exposición a este contaminante, ya que la exposición prolongada puede provocar problemas de salud graves y contribuir al deterioro ambiental.(1)

##Metodología

Visualización de datos
Los datos se representaron gráficamente para identificar patrones y tendencias a lo largo del tiempo. La visualización desempeña un papel fundamental en el análisis de datos, ya que facilita una comprensión más clara de las fluctuaciones y comportamientos de los contaminantes.

Adherencia a la Guía de Laboratorio
Durante la realización de la tarea, se revisaron y siguieron meticulosamente las instrucciones de la guía de laboratorio, la cual fue proporcionada en la plataforma Blackboard. Este procedimiento garantiza que el análisis se realice de manera organizada y cumpla con los estándares establecidos.
Descarga y Preparación de Datos

Para realizar el análisis de regresión, se descargó información de uno de los indicadores de calidad del aire utilizando la opción "Descargar datos diarios". Se trabajó con los datos de los años 2022 y 2023 referentes al material particulado PM10. Los datos fueron cargados en Colab Notebooks, donde se desarrolló todo el código necesario. Los pasos específicos incluyen:

La carga de datos de los años 2022 y 2023 correspondientes a PM10.
La implementación de la regresión.
El entrenamiento del modelo.
La conversión de datos para su análisis.
Análisis de artículos y búsqueda de información
Se revisaron diversos artículos científicos para comprender mejor la predicción del Índice de Calidad del Aire y el comportamiento del contaminante PM10. La búsqueda de información se realizó utilizando herramientas como Google Académico, con palabras clave como "Índice de Calidad del Aire", "PM10" y "material particulado". Esta revisión bibliográfica fue crucial para contextualizar y validar los resultados obtenidos en el análisis.

##Resultados

Tabla de base de datos

Figura 1:

<img width="866" alt="base de datos2022" src="https://github.com/user-attachments/assets/88b40710-0ac7-4a8a-961e-59c1275ffdfb">

Matriz de funcionamiento

Figura 2:

<img width="560" alt="matriz 2022" src="https://github.com/user-attachments/assets/d5e0fd72-a572-4d6c-a5e6-a8712759693a">

Valores de concentracion

Figura 3:

<img width="360" alt="valores concentracion 2022" src="https://github.com/user-attachments/assets/d423d5f0-cdf9-47e3-bd70-99492cd9c8ae">

Figura 4:

<img width="423" alt="daily 2022 1" src="https://github.com/user-attachments/assets/98ca99a3-9ee0-4c3b-aecd-a0bfe4b8d8f8">

Concentracion maxima diaria pm10 

Figura 5:

<img width="158" alt="concentracion maxima diarai 2022" src="https://github.com/user-attachments/assets/540e01c1-64da-4f64-9ca4-f426a95c969e">

Valor de AQI

Figura 6:

<img width="495" alt="valor diarai aqui 2022" src="https://github.com/user-attachments/assets/0db0f95c-3a29-45c6-8852-d6fa4baae253">

Regresion lineal valor real vs predicho AQI

Figura 7

<img width="495" alt="valor diarai aqui 2022" src="https://github.com/user-attachments/assets/8088c792-336f-472a-81d8-c9832fc034d8">

Histograma de residuos para verificar la normalidad

Figura 8

<img width="534" alt="histograma 2022" src="https://github.com/user-attachments/assets/6f3d0d02-d35f-445f-a5cb-429fdf987036">

Visualizacion de valores residuales vs predichos

Figura 9

<img width="487" alt="valores residuales 2022" src="https://github.com/user-attachments/assets/4eec3e81-5291-4915-80ec-3288bcb7f933">

Tabla de base de datos 2022

Figura 10

<img width="877" alt="tabla de base de datos 2022 2" src="https://github.com/user-attachments/assets/3929acee-183b-4b12-b56f-f4bbad2bcae0">

Data2023:

Base de datos

Figura 11

<img width="902" alt="base de datos 2023" src="https://github.com/user-attachments/assets/5efaa1dc-310b-4d97-91c0-6c6bd5598e4f">


Matriz funcionamiento 

figura 12

<img width="503" alt="matriz" src="https://github.com/user-attachments/assets/ada53495-360b-4cb5-aba0-54bb8ff65a50">

Concentracion pm10 vs AQI

Figura 13

<img width="429" alt="predicho" src="https://github.com/user-attachments/assets/1fe651e4-271c-43f3-b7b2-1a213de7ef46">


Tabla de base de datos

Figura 14

<img width="891" alt="datos 2023 2" src="https://github.com/user-attachments/assets/32ca824b-1e80-48db-9524-124c51f433b5">


Datos 2022 2023

Tabla base de datos

Figura 15:

<img width="719" alt="base de datos" src="https://github.com/user-attachments/assets/cf6f0e87-c5b0-4135-a697-e56caf49c5a1">

Matriz 

Figura 16

<img width="389" alt="matriz" src="https://github.com/user-attachments/assets/cf768780-5328-4b0b-8e9f-2b603f85af33">

Grafica de concentracion maxima diaria

Figura 17

<img width="364" alt="g1" src="https://github.com/user-attachments/assets/e8eed8ca-8a9b-40c7-88da-f214346dc2c7">

Grafica de densidad de concentracion maxima

Figura 18

<img width="299" alt="g2" src="https://github.com/user-attachments/assets/f2f1fa73-13ef-4697-9f97-b77cd3f5a4dc">

Grafica de valor diario de AQI

Figura 19

<img width="363" alt="g3" src="https://github.com/user-attachments/assets/2954de24-edba-4e86-a362-17122152d517">

Grafica de densidad AQI

Figura 20

<img width="299" alt="g4" src="https://github.com/user-attachments/assets/83389dec-79a4-4c28-a4a4-fb07c3de18ac">


Regresion lineal demuestra como el PM 10 impacta en el indice de calidad de aire

Figura 21

<img width="250" alt="vs daily aqi" src="https://github.com/user-attachments/assets/488d6f10-c6d8-4fd0-b78c-d825f34d97dd">

##Discusion

Después de realizar la predicción utilizando el método de regresión para analizar y explorar la relación entre la concentración de partículas PM10, que influye en el Índice de Calidad del Aire (AQI) en California, con los datos recopilados durante los años 2022 y 2023, se observó que la frecuencia de la concentración máxima diaria de PM10 en 24 horas versus el Índice de Calidad del Aire diario es crucial para entrenar el modelo y obtener resultados representativos. Utilizando el modelo de regresión, los datos se ajustaron para obtener predicciones más precisas del AQI, empleando métricas como el error absoluto medio, el error cuadrático medio y el puntaje R^2. Estos resultados destacan la relación entre la predicción y la concentración de PM10: a medida que aumenta la concentración de partículas, el Índice de Calidad del Aire también se eleva, lo que indica una peor calidad del aire.

Con estos datos, se puede predecir con mayor precisión el AQI de California, lo que contribuye a la salud pública y facilita la toma de decisiones para reducir la concentración de partículas PM10 en la atmósfera. Esto puede lograrse implementando medidas como el control de emisiones industriales, la reducción de quema de combustibles fósiles, y la gestión de incendios forestales, entre otras estrategias para mejorar la calidad del aire

##Bibliografia

1.Evaluación del PM10 en California - Bing. (s. f.). Bing. https://www.bing.com/search?q=+Evaluaci%C3%B3n+del+PM10+en+California&qs=n&form=QBRE&sp=-1&lq=1&pq=&sc=24-0&sk=&cvid=52451830C3D84D75AE6B207D684284AB&ghsh=0&ghacc=0&ghpl=

2.Quincho, J. P. R., & Dionicio, E. A. M. (2022). PRONÓSTICO DE LAS CONCENTRACIONES DE MATERIAL PARTICULADO EN EL AIRE (PM10) UTILIZANDO REDES NEURONALES ARTIFICIALES: CASO ESTUDIO EN EL DISTRITO DE ATE, LIMA. Revista de la Sociedad Química del Perú, 88(3). https://doi.org/10.37761/rsqp.v88i3.402

3.Meza, L. M., Quintero, M., García, R., & Ramírez, J. (2010). Estimación de Factores de Emisión de PM10 y PM2.5, en Vías Urbanas en Mexicali, Baja California, México. InformacióN TecnolóGica, 21(4). https://doi.org/10.4067/s0718-07642010000400007


