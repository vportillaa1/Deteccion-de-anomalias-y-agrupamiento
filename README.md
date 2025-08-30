# Detección de anomalías y técnicas de agrupamiento


## Introducción

El análisis de datos clínicos desempeña un papel fundamental en la detección temprana de riesgos y en la toma de decisiones médicas basadas en evidencia. En este estudio se trabaja con un dataset de cardiotocografía fetal (CTG), técnica ampliamente utilizada en obstetricia para monitorear la salud del feto durante el embarazo y el parto. El conjunto de datos incluye múltiples variables numéricas relacionadas con la frecuencia cardíaca fetal (FHR) y las contracciones uterinas (UC), a partir de las cuales se extraen indicadores que permiten clasificar el estado del feto en tres categorías: Normal, Sospechoso y Patológico (NSP).

1. Objetivos
   
• Objetivo 1: Realizar un análisis exploratorio de datos (EDA) del dataset de cardiotocografía (CTG), identificando las características estadísticas de las variables numéricas y categóricas, así como las correlaciones existentes entre ellas.
• Objetivo 2: Implementar la técnica de detección de anomalías Local Outlier Factor (LOF) para identificar valores atípicos locales que puedan alterar la estabilidad de futuros modelos de regresión o clasificación.
• Objetivo 3: Aplicar el algoritmo de agrupamiento OPTICS para segmentar el dataset en clústeres, interpretando los patrones encontrados y evaluando la calidad de la agrupación generada.

2. Desarrollo de la actividad
3.  
