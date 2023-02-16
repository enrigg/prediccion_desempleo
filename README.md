# Predicción de desempleo en España Noviembre 2022.

Este repositorio contiene el csv **predicciones.csv** donde viene la fecha y número de desempleados en España desde el 1 de Marzo de 2021.

<p align="center">
<img alt="" src="https://github.com/enrigg/prediccion_desempleo/blob/main/csv.png?raw=true">
</p>

También esta el script **predict_unemployment.ipynb** donde viene paso por paso las instrucciones para realizar la predicción de la serie temporal usando SARIMAX.

<p align="center">
<img alt="" src="https://github.com/enrigg/prediccion_desempleo/blob/main/predict.png?raw=true">
</p>

También se ha creado una variable simulando la **importancia del COVID** en el desempleo para ayudarnos con la precisión del modelo, al principio tenía mucha influencia en el output pero a medida que va pasando el tiempo esta influencia también va bajando.

<p align="center">
<img alt="" src="https://github.com/enrigg/prediccion_desempleo/blob/main/covd.png?raw=true">
</p>

Esto fue un proyecto para la clase **Machine Learning I** del *Máster en Tecnologías Big Data y Analítica Avanzada de ICAI*.
