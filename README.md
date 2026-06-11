Análisis de Experimento A/A/B para una Aplicación de Ventas
Descripción del proyecto

Este proyecto analiza el comportamiento de los usuarios dentro de una aplicación móvil de venta de productos alimenticios. El objetivo principal fue evaluar si un cambio en el diseño de la interfaz tenía un impacto significativo en la conversión de los usuarios mediante un experimento A/A/B.

Se trabajó con registros de eventos generados por los usuarios dentro de la aplicación, identificando las acciones realizadas en cada etapa del proceso de compra.

Objetivos:

Preparar y limpiar los datos para su análisis.
Analizar el comportamiento general de los usuarios.
Construir y evaluar el embudo de conversión.
Validar que los grupos de control (A/A) fueran estadísticamente equivalentes.
Comparar el grupo experimental (B) contra los grupos de control para determinar si el nuevo diseño generó cambios significativos.

Herramientas utilizadas

Python,
Pandas,
NumPy,
Matplotlib,
SciPy,
Jupyter Notebook,
Metodología

Preparación de datos:
Se cargó el conjunto de datos.
Se renombraron columnas para facilitar el análisis.
Se transformaron las fechas desde formato Unix Timestamp a formato datetime.
Se verificó la calidad de los datos y la existencia de valores anómalos.

Análisis exploratorio

Se estudió:

Número total de eventos.
Número de usuarios únicos.
Promedio de eventos por usuario.
Distribución temporal de los eventos.
Eventos más frecuentes dentro de la aplicación.

Construcción del embudo de conversión

Se analizaron las principales etapas del recorrido del usuario:

MainScreenAppear,
OffersScreenAppear,
CartScreenAppear,
PaymentScreenSuccessful

Posteriormente se calcularon las tasas de conversión entre cada etapa para identificar dónde se producía la mayor pérdida de usuarios.

Validación del experimento A/A

Antes de analizar el nuevo diseño, se compararon los grupos 246 y 247 para confirmar que ambos grupos de control presentaban comportamientos similares.

Se aplicaron pruebas estadísticas para verificar que no existieran diferencias significativas entre ellos.

Evaluación del experimento A/B

Una vez validados los grupos de control, se comparó el grupo experimental (248) con los grupos de control para determinar si el cambio de diseño generaba diferencias significativas en la interacción de los usuarios.

Las comparaciones se realizaron para cada evento relevante del embudo utilizando pruebas estadísticas de proporciones.

Resultados

Los grupos de control mostraron un comportamiento similar, validando la correcta ejecución del experimento A/A.
El embudo permitió identificar las etapas con mayor abandono de usuarios.
Las pruebas estadísticas indicaron que el nuevo diseño no produjo cambios significativos en las tasas de conversión de los usuarios.
Con base en los resultados obtenidos, no se encontró evidencia suficiente para afirmar que la nueva interfaz mejorara el rendimiento de la aplicación.

Conclusión

El análisis permitió validar la calidad del experimento y evaluar objetivamente el impacto del rediseño de la interfaz. Los resultados sugieren que el cambio visual implementado no generó mejoras estadísticamente significativas en el comportamiento de los usuarios ni en la conversión dentro del embudo de compra.