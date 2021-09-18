# Web Scraping:

Mini Proyecto de aplicar las metodologías de Web Scraping, para extraer información de una página web mediante Python.
Se decidió emplear la API de Selenium Python para realizar un script funcional y poder acceder a  páginas web de forma intuitiva y fácil a través de la funcionalidades que posee el Selenium WebDriver. 


* [Project Description](#project-description)
* [Workflow](#workflow)


## Project Description
Se seleccionó la pagina “us.shein.com” para extraer mediante la API de Selenium en Python los productos más populares de mujer. Adamas de cada producto extraído se obtuvo información del precio, valoración, numero de comentarios, imagen del producto, correspondencia de la talla, link y la categoría que pertenece.



## Workflow
Para la realización de este script se desglosó cada una de las acciones necesarias para obtener la información de cada producto. En este sentido se establecieron las funciones del script de la siguiente manera:
*Inicializador de la API Selenium WebDriver
*Extracción de los links de cada unos de los productos en la pagina “Más Populares”
*Extracción y guardado en un archivo “ropa_data.csv” alojado en una carpeta llamada "/extrated_data", donde está contenido la información de cada producto 
*Limpiar los datos guardados en el archivo “ropa_data.csv” 

Se utilizaron modulos como:
* Time
* Pandas
* Numpy
* bs4
* re
* os
* Selenium 

## Authors :pencil:
- Benjamin Kenyery 
