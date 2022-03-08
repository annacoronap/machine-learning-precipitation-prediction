Este estudio tiene el objetivo de desarrollar un algoritmo para predecir las precipitaciones. La base de datos ha sido extraida de la web del Servei Meteorològic de Catalunya, y corresponde a los datos registrados por la XEMA (Xarxa d'Estaciones Meteorològiques Automàtiques), y contiene datos des del 2009 al 2022 de 221 estaciones meteorológicas. 

En primer lugar, se lee y preprocesa la base de datos. Ésta supera los 30GB, por lo que se recurre a la librería pyspark. Luego se seleccionan las estaciones meteorológicas interesantes para tener una cantida notable de datos y diversidad de localización, y los datos se ordenan según necesidad.

Con los datos filtrados, se procede al entrenamiento mediante los diferentes métodos de regresión y clasificación, y se seleccionan los modelos con los que se han obtenido mejores métricas.
