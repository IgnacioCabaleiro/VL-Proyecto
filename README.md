# Análisis de Sentimiento de Tweets sobre el Municipio

## **Objetivo**
El objetivo de este proyecto es analizar las respuestas a los tweets del municipio para identificar y comprender las críticas negativas de los ciudadanos. Utilizando técnicas de Procesamiento de Lenguaje Natural (NLP) y modelado de temas, se busca extraer información que permita mejorar la gestión y la respuesta a los ciudadanos.

## **Alcance**
- **Recopilación de datos:** Recolectar tweets relacionados con el municipio utilizando la extensiòn de google Bardeen AI.
- **Limpieza y preprocesamiento de datos:** Eliminar menciones de usuarios, URLs, y caracteres especiales. Convertir los textos a minúsculas y eliminar stopwords.
- **Análisis de sentimiento:** Utilizar modelos de NLP para clasificar los tweets en categorías de sentimiento (positivo, negativo, neutral).
- **Modelado de temas:** Aplicar LDA (Latent Dirichlet Allocation) para identificar los temas más comunes en los tweets negativos.
- **Visualización:** Crear visualizaciones para mostrar las tendencias de críticas negativas a lo largo del tiempo y las palabras más comunes en los tweets.

## **Conclusiones**
- **Identificación de problemas comunes:** El análisis de sentimiento y el modelado de temas permitieron identificar los principales problemas y preocupaciones de los ciudadanos. Por ejemplo, temas recurrentes como  impuestos, fumigación, iluminaria y limpieza fueron destacados en los tweets negativos.
- **Resultados:** Considerando que este anàlisis se hizo con aproximadamente 300 tweets se obtuvo un buen desarrollo y anàlisis pero logicamente cuanto mas datos haya mejor resultado vas a poder obtener.
---

# Análisis de Calidad del Agua del Río de la Plata

## **Objetivo**
El objetivo de este proyecto es analizar los datos de calidad del agua del Río de la Plata para predecir mediante modelos como regresiòn logistica y arboles de decisiones el Indice de calidad del agua (ICA). El análisis se enfoca en diversos parámetros físicos, químicos y biológicos.

## **Alcance**
- **Recopilación de datos:** Utilizar datos recopilados de la pagina oficial del CIAM (Centro de informaciòn ambiental) para el analisis.
- **Limpieza y preprocesamiento de datos:** Convertir columnas con valores numéricos almacenados como texto a formatos numéricos. Manejar valores especiales como "<0.005" o ">0.5".
- **Análisis descriptivo:** Generar estadísticas descriptivas y visualizaciones para cada parámetro de calidad del agua.
- **Análisis de correlaciones:** Evaluar las correlaciones entre diferentes parámetros para identificar posibles fuentes de contaminación.
- **Clasificación de calidad del agua:** Utilizar índices de calidad del agua (ICA) para clasificar las muestras en diferentes niveles de calidad.

## **Conclusiones**
- **Identificación de parámetros críticos:** Los análisis identificaron parámetros como "coliformes fecales", "escherichia coli" y "microcistinas" como indicadores críticos de contaminación.
- **Variabilidad temporal y espacial:** Se observaron variaciones significativas en la calidad del agua a lo largo del tiempo y entre diferentes estaciones de monitoreo, lo que sugiere la influencia de fuentes puntuales y difusas de contaminación.
- **Recomendaciones para el monitoreo:** Los resultados destacan la importancia de un monitoreo continuo y detallado para detectar cambios en la calidad del agua y tomar medidas preventivas y correctivas adecuadas.

---

### **Requisitos**
Para reproducir estos análisis, asegúrate de tener instaladas las siguientes dependencias:
```bash
pip install pandas numpy scikit-learn matplotlib transformers
