# Proyecto-de-fin-de-modulo-8---Alfaro-Badillo-Cruz-Perez-Rupit


Introducción Analítica a la Ciencia de Datos
Módulo 8: Comunicación de resultados

Proyecto Final
Objetivo

El objetivo del proyecto es desarrollar un análisis completo de ciencia de datos a partir de datos reales, integrando las diferentes etapas vistas durante el curso:

    Selección y obtención de datos
    Exploración
    Limpieza y transformación
    Análisis
    Modelado
    Visualización
    Comunicación de resultados

Cada equipo recibirá un tema y una fuente principal de datos. Las propuestas de análisis y preguntas incluidas en esta guía con orientativas. Si durante la exploración del conjunto de datos, el equipo encuentra una pregunta diferente que resulte relevante o interesante, podrá desarrollarla siempre que esté justificada y tenga suficiente profundidad analítica.

Se puede complementar la fuente proporcionada con otros datos públicos siempre que se documenten adecuadamente y se explique su relevancia.
Instrucciones generales
Selección y obtención de datos

Cada equipo deberá explorar la fuente asignada y decidir el periodo utilizar, variables necesarias, unidad de análisis, si necesitan alguna fuente adicional. No es necesario usar todos los datos disponibles. Se debe documentar el procedimiento utilizado para la obtención de datos incluyendo en uso de APIs cuando corresponda.
Exploración y preparación

Antes de realizar el análisis se debe analizar la estructura y calidad de los datos, incluyendo tipos de variables, valores faltantes, registros duplicados, valores atípicos, errores o inconsistencias, cambios metodológicos en la fuente, etc.

Las decisiones de limpieza deben justificarse.
Pregunta de investigación

Formular una pregunta de investigación y las preguntas secundarias que consideren necesarias. La pregunta debe ser suficientemente específica como para poder responderse mediante los datos disponibles. Con esto deberán documentar una hipótesis, variable objetivo, variables explicativas, población de interés, unidad de análisis, periodo y alcance geográfico.
Análisis exploratorio

Comprender el fenómeno y construir evidencia que ayude a responder la pregunta principal. Cada elemento debe tener un propósito dentro de la historia que quieren comunicar.
Modelado

Deben incluir al menos un modelo o técnica analítica adecuada para el problema planteado.

Dependiendo de la naturaleza de los datos pueden usar por ejemplo modelos de regresión, clasificación, árboles, clustering, reducción de dimensionalidad, deteccción de anomalías, series de tiempo, redes neuronales, procesamiento de texto, sistemas de recomendación, simulación, aprendisaje por refuerzo, etc.

La selección del modelo debe responder a la pregunta de investigación y ser desarrollado adecuadamente según corresponda: separar entrenamiento y validación, seleccionar métricas adecuadas, comparar alternativas, interpretar resultados, identificar limitaciones, etc.
Visualización final

Desarrollar una visualización publicada y accesible mediante URL.

El formato es libre dependiendo de las características del proyecto, por ejmeplo: aplicación web, dashboard o sitio web.

No se evaluará la herramienta utilizada, sino la capacidad de la visualización para comunicar los resultados. La solución debe, como mínimo, permitir entender:

    ¿Qué ocurre?
    ¿Qué patrones o relaciones encontraron?
    ¿Qué aporta el modelo?
    ¿Cuál es la conclusión principal?

Repositorio

Compartir la liga del repositorio que permita reproducir el análisis con el código utilizado, instrucciones para reproducir el análisis, documentación del análisis completo.
Reporte

El entregable es un reporte breve que expliqye el proyecto:

    Problema y contexto
    Pregunta principal
    Datos y procedencia
    Alcance
    Principales decisiones de limpieza
    Metodología
    Modelo
    Principales resultados
    Conslusiones
    Limitaciones
    Posibles extensiones

Se deben enfocar en qué hicieron, por qué lo hicieron y qué aprendieron.
Evaluación

La evaluación final incluirá la defensa oral del proyecto. Cada equipo dispondrá de 5 minutos para presentar el proyecto en los que deben explicar:

    Problema
    Datos
    Análisis y modelado
    Resultados
    Canclusión

Además se realizarán dos preguntas que serán evaluadas. Las preguntas pueden dirigirse a cualquier integrante del equipo, por lo que TODOS los integrantes del equipo deben ser capaces de explicar las decisiones tomadas durante el análisis, las estructura del proyecto, el código, etc.

Una persona que no pueda explicar las decisiones metodológicas o analíticas del proyecto podrá obtener una calificación individual diferente a la del resto del quipo.
Fechas

El reporte con las especificaciones mencionadas antes deberán enviarse por correo antes del lunes 28 de septiembre incluyendo la lista de los integrantes del equipo. La presentación de los proyectos será los días 01 y 06 de octubre en un horario de 18:00 a 20:00 hrs. El día de exposición de cada equipo será aleatorio.

PROYECTO 14. SEQUÍA EN MÉXICO


Tema propuesto: Analizar la evolución territorial y temporal de la sequía en México.

Datos: Programa Nacional Contra la Sequía — PRONACOSE

Propuesta de análisis: Estudiar qué regiones presentan mayor exposición o persistencia de sequía y cómo cambia la situación a través del tiempo.

Posibles preguntas:

    ¿Qué municipios presentan sequías más frecuentes?
    ¿Dónde son más persistentes?
    ¿Se pueden identificar regiones con patrones similares?
    ¿Existe relación con variables climatológicas?
    ¿Puede anticiparse un cambio en la intensidad de sequía?

Preguntas abordadas:

    ¿Cómo se distribuye la intensidad de la sequía entre los municipios de México en enero de 2026 y qué características presentan los municipios con mayor afectación?
    ¿Qué estados concentran la mayor cantidad de municipios con sequía?
    ¿Qué categorías de sequía (D0–D4) predominan?
    ¿Qué regiones presentan las categorías más intensas?
    ¿Existen grupos de municipios con patrones similares de afectación?
    ¿Existe alguna relación entre la intensidad de sequía y la vulnerabilidad social, económica o ambiental?

Modelos posibles: Clasificación, clustering territorial, modelos temporales o forecasting.

Datos complementarios sugeridos: Temperatura y precipitación, niveles de presas, disponibilidad de agua, agricultura, población, uso de suelo y producción agrícola.

INFORMACIÓN CONTENIDA EN LA BASE DE DATOS 

Indicadores de Intensidad de Sequía (Escala NADAM / CONAGUA)
El Monitor de Sequía de México sigue la metodología del North American Drought Monitor (NADAM). Las columnas numéricas o binarias asociadas representan las siguientes categorías:
Sin Seca / Sin Sequía: Municipio sin afectación de precipitación o humedad.
D0 (Anormalmente Seco): Condición de sequedad previa o posterior a una sequía; no se considera sequía en sí, sino una alerta temprana.
D1 (Sequía Moderada): Afectaciones leves en cultivos y pastos; riesgo bajo de incendios forestales.
D2 (Sequía Severa): Probables pérdidas en cultivos/pastos; escasez común de agua.
D3 (Sequía Extrema): Pérdidas mayores en cultivos y pastos; escasez generalizada de agua.
D4 (Sequía Excepcional): Pérdidas excepcionales en cultivos y pastizales; situación de emergencia por escasez de agua en embalses y pozo.
Clave_Intensidad / Categoria: Valor textual o código numérico (0 a 4 o D0 a D4) que asigna la categoría máxima que registró el municipio en el mes.

Indicadores Climatológicos Integrados
Los datos de origen con los que CONAGUA / SMN calcula la columna final del municipio se basan en múltiples índices estandarizados:
SPI (Standardized Precipitation Index): Índice Estandarizado de Precipitación.
SPEI: Índice de Precipitación y Evapotranspiración Estandarizado.
VHI / NDVI: Índices de salud y verdor de la vegetación obtenidos por satélite (AVHRR/MODIS).
Porcentaje de Humedad del Suelo: Estimación del déficit hídrico en la capa superficial y profunda del suelo.

NOTA SOBRE AUTORÍA Y COMPRENSIÓN
Para el desarrollo del proyecto es posible usar documentación, bibliotecas, recursos en línea y herramientas de inteligencia artificial como apoyo. Sin embargo, durante la evaluación oral deberán demostrar comprensión de TODO lo entregado.

Cualquier integrante debe poder explicar cómo se obtuvieron los datos, cómo se limpiaron, por qué se usó cierto modelo, cómo se evaluó, qué significa el resultado, cómo se construyó la visualización, cuáles son las principales limitaciones, etc.

La incapacidad para explicar alguna parte del trabajo podrá afectar la calificación individual.

