

# Proyecto: Visualización de datos

## Análisis de bases COVID-19 México

Se realizó el analisis de las bases de México historias de enero a noviembre 2020, esto con el fin de poder visualizar el incremento de casos y analizar variables secundarias, como enfermedades que se presentan en conjunto con este padecimiento.

Dentro de este README encontrará la liga de un dashboard en DataStudio en el que se concentra la presentación final, y en el archivo ipynb econtrará otras gráficas que cumplen con el requirimiento de este proyecto.

---

## Limpieza de datos

Dentro de este repositorio podrás encontrar el zip que contiene la base original, la cual fue limpiada y se guardaron diferentes csv para cada necesidad del análisis.

 - Se transformaron la gran mayoría de datos a booleanos, puesto que la base original tenía otra forma de clasificar entre True y False
  - Se sustituyeron el nombre de los estados para que pudieran coincidir con el id del geojson que se uso para realizar mapas en colab por medio de folium.
 - Dejo aqui la liga del **geojson usado** el cual contienen las coordenadas por estado: https://gist.githubusercontent.com/ponentesincausa/46d1d9a94ca04a56f93d/raw/a05f4e2b42cf981e31ef9f6f9ee151a060a38c25/mexico.json

## Dashboard 

La liga es la siguiente:

https://datastudio.google.com/reporting/2f0a95a7-8fcd-4445-bcfe-5b1214b6e84b

