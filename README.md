Trabajo Final Integrador: Análisis de Datos - UTN-FRP

Enfoque del análisis: El mercado de alquiler temporario (Airbnb) en CABA desde la perspectiva del "Viajero Inteligente" (optimización de la relación calidad-precio).

Estructura del repositorio

analisis_airbnb_caba.ipynb: Notebook de Python con el código utilizado para la preparación y limpieza de los datos (conversión de tipos, tratamiento de valores nulos y filtrado de precios atípicos mediante percentiles), el cálculo de indicadores estadísticos (medianas y correlación de Spearman) y la generación de las ocho visualizaciones del análisis exploratorio (Matplotlib y Seaborn).

listings_limpio.csv: Dataset procesado final, con 20.058 registros y 6 variables seleccionadas para el análisis (neighbourhood_cleansed, room_type, price, review_scores_rating, number_of_reviews, accommodates).

El dataset original completo (listings.csv.gz, con más de 29.000 registros y 90 columnas) se puede descargar desde este enlace de Drive: https://drive.google.com/file/d/1tNUwU8PVJ1LUK-ODT7iGROFLJ7wQ_3vJ/view?usp=sharing

Alcance del repositorio

Este repositorio se presenta como material complementario del Trabajo Final Integrador de Introducción al Análisis de Datos de la Tecnicatura Universitaria en Programación (UTN-FRP). Su finalidad es documentar las herramientas, el código y los datos utilizados durante el desarrollo del trabajo.

Las interpretaciones de los gráficos, la secuencia de análisis completa (Pregunta → Evidencia → Interpretación → Respuesta), las conclusiones, las recomendaciones estratégicas para el usuario final y las limitaciones metodológicas se desarrollan de forma exhaustiva en el informe final entregado a la cátedra (formato PDF).

Nota técnica: Los datos analizados provienen de Inside Airbnb (septiembre de 2026) y representan una "foto estática" del mercado. Las publicaciones evaluadas no miden ocupación real, sino que se enfocan en los precios de lista y la percepción de calidad (reseñas) para encontrar patrones de ahorro turístico.

