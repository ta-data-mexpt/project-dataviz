Proyecto Visualizing-Real-Data

 

Guillermo Arturo García Ramírez 

A partir de información pública de la Encuesta Nacional sobre Disponibilidad y Uso de Tecnologías de Información y Comunicaciones en los Hogares - ENDUTIH (https://www.inegi.org.mx/programas/dutih/2019/) del Instituto Nacional de Estadística Geografía e Informática (INEGI) se hace un análisis general de telecomunicaciones fijas. Asimismo, con información pública del Banco de Información de Telecomunicaciones -BIT (https://bit.ift.org.mx/BitWebApp/descargaArchivos.xhtml) del Instituto Federal de Telecomunicaciones (IFT) se hace un análisis general del consumo en el mercado mexicano del servicio de telefonía móvil.

Para las telecomunicaciones fijas se analiza su tendencia en el tiempo de los tres principales servicios (internet, televisión de paga y telefonía fija), la evolución de contratar los servicios en paquetes sintéticos o en paquetes integrados y cuáles son los paquetes y servicios más contratados por los hogares en México.

Para las telecomunicaciones móviles se analiza la composición de las líneas totales en  líneas de prepago y líneas de pospago, así como la tendencia de estas líneas en el tiempo. 

Los archivos de la ENDUTIH 2019 y los del BIT estaban en formato "CSV" desde su descarga en las fuentes originales. Los archivos de ENDUTIH 2015 a 2018 en las fuentes de descarga están en formato "DBF", por lo que primero se abrieron en Excel para convertirlos a un archivo "CSV" y ya poder abrirlos en Jupyter Notebook y trabajar con ellos.

Glosario:

SBAF: Servicio de banda ancha fija (internet).
STAR: Servicio de televisión y audio restringido (Televisión de paga).
STF: Servicio de telefonía Fija.
STM: Servicio de telefonía móvil.
Paquete integrado: los servicios contratados provienen de un solo proveedor, es decir, solo pagar una factura por todos los servicios.
Paquete sintético: los usuarios/hogares contratan los servicios con diferentes proveedores, es decir, la demanda arma sus paquetes de acuerdo a sus necesidades y preferencias.
Prepgago: cuando el usuario paga por los servicios de telecomunicaciones antes de utilizarlos. Por ejemplo, fichas o recargas electrónicas.
Pospago: cuando el usuario paga por los servicios de telecomunicaciones después de utilizarlos. Por ejemplo, renta mensual por contrato.