# vanguard-ab-test

Este proyecto consiste en un test A/B para comparar dos versiones de la web de una compañía (la versión original y la versión mejorada, con una nueva interfaz).
La compañía Vanguard quiere mejorar la interfaz de su web y para comprobar si es más efectiva que la antigua, decide hacer un experimento con clientes que ya usan la plataforma y así ver qué modelo es más efectivo. 
La primera parte del proyecto consiste en la limpieza y análisis estadístico de los datos a través de Python. De los datos proporcionados sobre los clientes que han participado en el experimento, dividimos los usuarios en dos grupos distintos: Grupo Control (los que han usado la web original) y Grupo Test (los que han probado la nueva interfaz). Primero realizamos un análisis demográfico de los usuarios y después planteamos una serie de métricas para comparar los comportamientos de ambos grupos. Plantemos varias hipótesis para reafirmar la comparación entre grupos y llegar a conclusiones más solidas.
En la segunda parte del proyecto, llevamos todos nuestros análsis y datos ya limpios a Tableau para mostrar de una manera visual las métricas implementadas y los resultados de las hipótesis y el Test A/B.

La estructura del repositorio se basa en un README que explica el proyecto, las fases del proceso y el flujo de ejecución. Seguido de los notebooks donde se puede encontrar el análisis de datos y un documento de Tableau para poder ver los Dashboards creados para la visualización de este proyecto. 

El flujo de ejecución de este proyecto empezaría por el archivo Vanguard_ABTEST_Cleaning.ipynb, que recoge la limpieza de los datos de los que parte el proyecto. Después, el notebook Vanguard_ABTest_Analysis.ipynb, que incluye el análisis univariante, bivariante, análisis de KPIs y métricas y planteamiento y ejecución de los test de hipótesis. Por último, en el archivo Vanguard_ABTest.twbx encontramos el acceso a la visualización de los datos analizados en Tableau, con todas las hojas de trabajo creadas, así como los Dashboards en los que se recogen las conclusiones finales del proyecto.

La autoría del proyecto pertenece a Natalia Labrador.
