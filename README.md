### Análisis de Procesos: Planta de Tratamiento de Aguas Residuales Urbanas

El objetivo de este proyecto es analizar los datos operativos de una planta de tratamiento de aguas residuales para identificar patrones de comportamiento, clasificar anomalías y establecer las condiciones críticas que generan fallas en la calidad del agua de salida. 

**Proceso de análisis**
1.	Limpieza y Transformación: Conversión de tipos de datos, manejo de registros inconsistentes  y transformación de parámetros fisicoquímicos a unidades de carga para un análisis de masa real. 
2.	Clasificación de Eventos: Categorización de los registros de operación según la acumulación de anomalías para identificar si las desviaciones corresponden a eventos aislados o fallas sistémicas en el tren de tratamiento.
3.	Análisis Hidráulico y de Carga: Evaluación de la correlación entre el régimen hidráulico y la eficiencia en la remoción de sólidos. 
4.	Estudio de Estacionalidad: Identificación de tendencias temporales en los días de operación.
   
**Conclusiones**

•	Se identificó un cambio sistemático en el régimen hidráulico durante eventos anómalos, con incrementos del 10% en el caudal medio, lo que reduce el tiempo de retención y favorece el arrastre de sólidos. 
•	Durante eventos atípicos, la carga a la salida de Sólidos Sedimentables (SED) y Suspendidos (SS) aumenta en un 120.5% y 23.8% respectivamente, en comparación con la operación normal.
•	Los eventos severos muestran una perturbación distribuida que se intensifica aguas abajo, mientras que los eventos operativos suelen ser fallas localizadas en unidades específicas. 
•	Los meses de mayo y octubre destacan como periodos críticos de sobrecarga, probablemente asociados a ciclos hidrológicos intensos. 
•	Se detectaron incrementos de carga en etapas intermedias que sugieren ingresos adicionales de caudal no medido o recirculaciones internas no controladas. 

**Recomendaciones**

•	Evaluar el estado estructural de las unidades de tratamiento para identificar posibles fallas o averías.
•	Identificar y monitorear rutas hidráulicas alternas que se generen durante eventos de alta precipitación, con el fin de evaluar su impacto en la distribución del flujo y en la eficiencia del tratamiento.
•	Diseñar e implementar un plan de acción para mitigar la variabilidad del caudal durante temporadas de alta precipitación.
•	Estandarizar la frecuencia y los protocolos de monitoreo de las condiciones operativas de la planta.
•	Establecer un cronograma de mantenimiento preventivo que incluya la remoción periódica de lodos acumulados y la eliminación de zonas muertas que favorezcan el arrastre de sólidos.

**Archivos del proyecto**
**[Notebook: Análisis de Carga y Diagnóstico Operativo]( https://github.com/KatPG/diagnostico-operativo-ptar/blob/main/water_plant_eda.ipynb)**

**[Dataset Original](https://archive.ics.uci.edu/dataset/106/water+treatment+plant)**

