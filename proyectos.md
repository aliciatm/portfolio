---
layout: default
title: Proyectos
permalink: /proyectos/
---

# 📁 Proyectos

Aquí se puede explorar algunos de los proyectos en los que he trabajado, con enlaces a repositorios y descripciones más detalladas.
*(¡Pendiente de actualizar con más proyectos!)*

## 📚 Índice de proyectos

- [La caída de la propiedad de vivienda entre los jóvenes en España: diferencias entre municipios](#la-caida-de-la-propiedad-de-vivienda-entre-los-jovenes-en-españa-diferencias-entre-municipios)
- [Trabajo de Fin de Grado: El alquiler como estrategia de emancipación residencial de los jóvenes](#trabajo-de-fin-de-grado-el-alquiler-como-estrategia-de-emancipacion-residencial-de-los-jovenes)
- [Análisis de Satisfacción de los Usuarios: Identificación de Factores Clave para Mejorar la Atención al Ciudadano](#análisis-de-satisfacción-de-los-usuarios-identificación-de-factores-clave-para-mejorar-la-atención-al-ciudadano)

---

## La caída de la propiedad de vivienda entre los jóvenes en España: diferencias entre municipios
Investigación sociológica cuantitativa realizada en el marco de una Beca de Colaboración del Ministerio de Educación y
Formación Profesional, centrada en **analizar las diferencias entre municipios en el aumento del alquiler juvenil** en los
últimos años. Mi objetivo era conocer si, pese a que en España se observa una disminución generalizada de la propiedad de vivienda entre la población joven emancipada, **¿esto ocurre en todo el territorio?** ¿En qué municipios o regiones no ocurre esto? ¿A qué variables o **características regionales** podría atribuirse esta diferencia?

El trabajo se basó en recopilar **datos de fuentes oficiales**, principalmente del **INE**, como los microdatos del Censo de Población y
Viviendas, así como otras estadísticas del mismo organismo. Otros datos procedían de fuentes como la Agencia Tributaria y de estadísticas regionales publicadas por las comunidades autónomas, e incluso se obtuvieron datos mediante técnicas de data scraping.

Conforme iba recopilando datos relevantes, utilicé **R** para **limpiar y procesar** la información procedente de distintas fuentes, homogeneizándola para poder integrarla en una única base de datos. El resultado fue un conjunto con **584 municipios y 55 variables**.

Una vez construida esta base de datos, llevé a cabo una **regresión lineal** para analizar cómo distintas variables —como el precio de la vivienda, la tasa de desempleo juvenil o la cantidad de viviendas turísticas— influían en mi variable dependiente: **la variación en el porcentaje de población joven emancipada que residía en propiedad entre 2011 y 2021**. Por otra parte, realicé un **análisis de clústeres** para identificar grupos de municipios con comportamientos residenciales y características similares.

Para visualizar los resultados, desarrollé una aplicación en **Shiny** en la que se pueden consultar mapas interactivos con datos sobre los regímenes de tenencia, explorar los resultados de la investigación y examinar los clústeres identificados. Se puede consultar la aplicación en el siguiente enlace, aunque debido a las limitaciones del servidor donde se aloja, es posible que en ocasiones se encuentre inactiva hasta que vuelva a activarla manualmente.

📊 [Ver Shiny App](https://aliciatm.shinyapps.io/Visualizations_TFM/)

👉 [Ver repositorio en GitHub](https://github.com/aliciatm/TFM_2024_aliciatm)


<img src="../assets/img/dif_ownership.png" alt="Diferencia de propiedad 2011-2021" width="550" />


## Análisis de Satisfacción de los Usuarios: Identificación de Factores Clave para Mejorar la Atención al Ciudadano
Al analizar la satisfacción de los usuarios de un servicio, no solo buscamos conocer el nivel de satisfacción, sino también **identificar las áreas o aspectos más importantes para mejorar.**. Sin embargo, uno de los problemas más frecuentes al preguntar directamente a los usuarios sobre qué aspectos consideran más importantes (como la rapidez en la atención, la claridad de la comunicación o el espacio en la sala de espera) es que, por lo general, todos los aspectos se valoran muy importantes, lo que dificulta la priorización de las mejoras.

En colaboración con Aiteco Consultores, participé en un proyecto destinado a **analizar las encuestas de satisfacción de los usuarios** para la Oficina de Información y Atención al Ciudadano del Cabildo de Lanzarote. El objetivo principal de este análisis fue detectar las áreas con margen de mejora en la atención al ciudadano, mediante la **identificación de factores clave que influían en la satisfacción de los usuarios.**

Para evitar el problema mencionado anteriormente, en el cuestionario no se preguntó directamente por la importancia que otorgaban a cada aspecto, sino que utilicé una **regresión de componentes principales**. Esta técnica estadística permite discernir de forma cuantitativa la importancia relativa de cada uno de los ítems que se incluyen en la encuesta, en relación con la calificación general de satisfacción que los usuarios asignan al servicio. De esta manera, fue posible identificar los principales factores que influían en la satisfacción y priorizar las áreas de mejora en función de su impacto en la percepción global del servicio.

Además, realicé un **análisis descriptivo** de los datos mediante tablas cruzadas y visualizaciones generadas en R para facilitar la interpretación de los resultados y aportar claridad sobre las tendencias en la satisfacción de los usuarios. Finalmente, toda la información procesada y los resultados obtenidos fueron presentados a través de un informe detallado, los cuales sirvieron como base para implementar mejoras en la calidad de la atención al ciudadano.

<img src="../assets/img/areas_mejora.png" alt="Áreas de mejora" width="550"/>


## Trabajo de Fin de Grado: El alquiler como estrategia de emancipación residencial de los jóvenes

Para mi Trabajo de Fin de Grado, desarrollé una investigación basada en el análisis de datos cuantitativos utilizando SPSS. Este proyecto aborda el fenómeno del **aumento del alquiler entre las personas jóvenes**, utilizando los datos de la **Encuesta Jóvenes y Vivienda**, elaborada por el Centro de Investigaciones Sociológicas (CIS). El objetivo era conocer qué variables, a nivel de individuo, influyen en la probabilidad de residir de alquiler.

En primer lugar, realicé un **análisis descriptivo** para examinar la prevalencia del alquiler juvenil y las condiciones asociadas, como la cuantía, localización y características residenciales. A continuación, llevé a cabo una **regresión logística binaria** con el fin de explorar cómo distintas variables —como el género, la nacionalidad o el nivel de estudios— influyen en la probabilidad de que una persona joven emancipada resida en régimen de propiedad o de alquiler.

En el repositorio se puede consultar la sintaxis en SPSS que utilicé para llevar a cabo el proceso de limpieza de la base de datos y los análisis realizados.

👉 [Ver repositorio en GitHub](https://github.com/aliciatm/Sintaxis-TFG-alquiler-jovenes)


<img src="../assets/img/reg_laboral.png" alt="Régimen de tenencia x Relación Laboral" width="450">

