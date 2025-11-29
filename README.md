# Trabajo de grado: 

INTELIGENCIA ARTIFICIAL APLICADA A LA SELECCIÓN DE BECADOS: UNA PROPUESTA DE OPTIMIZACIÓN DEL PROGRAMA DE BECAS EN EAFIT

**Autora: Luz Adriana Yepes Arias**

Este repositorio contiene los notebooks, datos procesados y modelos utilizados para el desarrollo del proyecto de grado “Inteligencia artificial aplicada a la selección de becados: una propuesta de optimización del programa de Becas en EAFIT”.

El proyecto está compuesto por cinco notebooks que se complementan entre sí y que conforman el flujo total del análisis, la exploración de datos y la construcción de modelos predictivos para el programa Becas Talento de la Universidad EAFIT.

Los datos originales de la convocatoria no se cargan ni se comparten en este repositorio, debido a su carácter confidencial y a la politica de protección y tratamiento de datos. En su lugar, cada notebook trabaja con datasets derivados y anonimizados, cargados como df_model, los cuales contienen únicamente las variables necesarias para cada modelo. Estos están nombrados deacuerdo con el modelo en los que fueron utilizados.

Cada notebook cumple una función específica dentro del proceso: 

+ El archivo EDA_proyecto_de_grado desarrolla el análisis exploratorio completo, la limpieza de variables, ingeniería de caracteristicas y definición final de los df_model utilizados posteriormente en la etapa de modelado.

+ El notebook Modelos_clasificación_AprobadavsNegada predice si un aspirante será aprobado o negado, implementando varios algoritmos de clasificación y comparando su desempeño.

+ El notebook Clasificación_porcentaje_beca trabaja con un df_model diseñado para categorizar el porcentaje de beca en niveles y entrenar modelos multiclase capaces de anticipar el rango de apoyo económico asignado.

+ El notebook Modelos_clasificación_matriculado_nomatriculado tiene los modelos utilizados para predecir si el estudiante finalmente usa o no la beca, permitiendo analizar la efectividad real del programa. Adicionalmente, viene un notebook donde se revisó la linealidad de las variables explicatorias con la variable objetivo.

En conjunto, estos notebooks documentan de forma ordenada y reproducible el flujo completo del proyecto, desde la exploración inicial de los datos hasta la construcción y evaluación final de los modelos predictivos.

**NOTA:** Los notebooks están diseñados para ejecutarse en Google Colab, por lo que no requieren configuración avanzada.


