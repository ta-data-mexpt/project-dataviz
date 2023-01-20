![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Visualizing Real World Data

## Cómo hice este proyecto

Hace algunos años trabajaba como periodista y el análisis de bases de datos era parte normal de mi trabajo. Recibir archivos con información para analizar y descubrir insights relevantes es algo común, así que hacer este proyecto fue de cierta forma retomar esa tarea que alguna vez hice.

Cuando encontré la [Awesome Public Data Sets](https://github.com/awesomedata/awesome-public-datasets) estuve explorando un poco los datasets relacionados con el gobierno de mi país, México. Ahí descubrí que el gobierno tiene el espacio público https://datos.gob.mx/ y encontré un dataset de la Procuraduría General de Justicia con información de las carpetas de investigación abiertas en la CDMX entre 2016 y 2019. 

Bajé el archivo .csv y lo trabajé primero en Jupyterlab para limpiarlo, aunque realmente estaba bastante organizado. Lo único que hice fue unir columnas que estaban duplicadas. 

Como siguiente paso, lo abrí en Tableau y fue ahí en donde comencé a explorar los datos. 
Elegí el top 5 de delitos y eliminé la "Denuncia de hechos", que no es un delito como tal. 
Después, noté que había muchas categorías separadas para diferentes tipos de robo, de modo que los agrupé, lo que permitió ver que en el top 5 de delitos, 4 de ellos son diferentes tipos de robo y solo 1 era diferente, la violencia familiar. Marqué con otro color distinto este último, mientras que los robos los dejé en la misma gama de colores.

Lo siguiente que hice fue explorar los delitos y hechos con menos denuncias y encontré algunos con nombres extraños y de cierto modo llamativos, como bigamia, robo de fluidos, revelación de secretos, contagio venéreo y muerte por congestión alcohólica. También los representé en una gráfica y decidí enfocarme en las muertes por congestión alcohólica. Descubrí que hubo una caída en los datos del último año del dataset, debido a que los registros se cortan en junio por un cambio en la dependencia que los originó. Traté de predecir a través de una gráfica si los siguientes meses seguirían las tendencias, pero se descubrió que no era así. 

Finalmente, representé un mapa con cruces para señalar los puntos donde se presentaron las muertes y cerré con un mapa de calor para identificar la zona en la que este hecho sucedió con más frecuencia.

Mi proyecto se puede encontrar en: https://public.tableau.com/app/profile/gilda5256/viz/CarpetasPGJ2016-2019/Portada?publish=yes
