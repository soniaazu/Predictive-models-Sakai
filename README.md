**Predictive Models for Sakai Data**  
Este repositorio contiene los recursos necesarios para replicar y experimentar con los modelos predictivos desarrollados a partir de los datos de Sakai. El propósito de este proyecto es proporcionar un conjunto de datos estructurados y un pipeline de modelado que permita predecir variables clave relacionadas con el rendimiento estudiantil en la plataforma educativa Sakai.

**Contenidos del repositorio**  

*datos_tabla_modelo_prediccion.csv:*  
Este archivo CSV contiene la tabla final que se utilizó como origen para el desarrollo de los modelos predictivos. Los datos han sido previamente limpiados y estructurados, y están listos para ser utilizados en experimentos de modelado predictivo.

*tabla_modelo_prediccion.sql:*  
Este archivo SQL incluye las consultas necesarias para derivar la tabla final a partir del conjunto de datos original. Puedes utilizar estas consultas para replicar el proceso de obtención de los datos de origen en un entorno SQL.

*modelo_predicciones_final.ipynb:*  
Este notebook en Python documenta el desarrollo completo de los modelos predictivos, utilizando algoritmos como Random Forest, XGBoost y LightGBM. Incluye la carga de datos, el preprocesamiento, la construcción de los modelos y la evaluación de su precisión.

**Propósito del proyecto**  
El objetivo de este proyecto es proporcionar una herramienta para la predicción de resultados educativos basados en datos de rendimiento estudiantil extraídos de la plataforma Sakai. Los modelos predictivos desarrollados aquí pueden ser utilizados para identificar patrones de comportamiento estudiantil que ayuden a mejorar las intervenciones educativas.

**Este repositorio está pensado para:** 

- Investigadores interesados en la minería de datos educativos.
- Profesionales de ciencia de datos que deseen experimentar con modelos predictivos en educación.
- Cualquier persona interesada en el uso de aprendizaje automático para mejorar la experiencia educativa.

**Cómo utilizar este repositorio**  
- Descarga los archivos datos_tabla_modelo_prediccion.csv y tabla_modelo_prediccion.sql.
- Si deseas replicar el proceso de obtención de la tabla, ve al repositorio https://github.com/soniaazu/Dataset-Sakai para obtener las tablas oirgen de la base de datos. Después, carga el archivo SQL en tu sistema de gestión de bases de datos.
- Carga el archivo modelo_predicciones_final.ipynb en tu entorno de Jupyter Notebook o Google Colab para ejecutar los modelos y analizar los resultados.
