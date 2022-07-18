# Scrapping de tablas de referencia de JDE
Este es un ejercicio simple de web scrapping sobre en https://jde.erpref.com en esta web podemos encontrar tres esquemas diferentes:

* 920
* 910
* 812

En el codigo podes cambiar el valor de la variable **_schema_** por cualquiera de esos tres, para descargarlos a gusto.

## Librerias usadas

Dejo el listado de las librerias utilizadas con el link directo a sus documentaciones por existen dudas.

- [Pandas](https://pandas.pydata.org/docs/)
- [Requests](https://requests.readthedocs.io/en/latest/user/quickstart/)
- [Warnings](https://docs.python.org/3/library/warnings.html#)
- [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/)

## Exportación

Al final de script se busca exportar en **_Excel_** pero tambien dejo comentado **_CSV_**.