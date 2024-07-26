# scraping_python

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Selenium-4.0%2B-yellow)](https://www.selenium.dev/)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.11.1-green)](https://www.crummy.com/software/BeautifulSoup/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0.3-blue)](https://pandas.pydata.org/)
[![Openpyxl](https://img.shields.io/badge/Openpyxl-3.1.2-blue)](https://openpyxl.readthedocs.io/en/stable/)
[![Undetected Chromedriver](https://img.shields.io/badge/Undetected%20Chromedriver-3.3.0-orange)](https://github.com/ultrafunkamsterdam/undetected-chromedriver)
[![Webdriver Manager](https://img.shields.io/badge/Webdriver%20Manager-3.8.6-red)](https://github.com/SergeyPirogov/webdriver_manager)



- Descargar de la pagina web del supermercado todos los articulos de la seccion de almacen, tantos sus precios como las ofertas por articulos

# Proyecto de Scraping en Supermercado

Este proyecto demuestra cómo realizar scraping en una página web de un supermercado para extraer información sobre productos. Los datos extraídos incluyen nombres de productos, precios y ofertas, y se guardan en archivos separados por categoría.

## Objetivo

El objetivo principal del proyecto es:

- Realizar scraping en la página de un supermercado para obtener datos de productos.
- Extraer información relevante, como nombres de productos, precios y ofertas.
- Organizar los datos en archivos Excel por categoría para análisis posterior.

## Funcionalidades

- **Extracción de Datos**: Extrae nombres, precios y ofertas de productos de una página web dinámica.
- **Manejo de Contenido Dinámico**: Utiliza técnicas para interactuar con botones de "Mostrar más" y desplazar la página para cargar todo el contenido.
- **Almacenamiento**: Guarda los datos en archivos Excel separados por categoría.

## Tecnologías Utilizadas

- **Selenium**: Para automatizar la navegación y el scraping de la página web.
- **BeautifulSoup**: Para analizar el contenido HTML y extraer la información necesaria.
- **Pandas**: Para manejar y guardar los datos en archivos Excel.
- **undetected_chromedriver**: Para evitar la detección de automatización por parte del navegador.

## Instalación

Para ejecutar este proyecto, necesitas tener Python y las siguientes librerías instaladas:

- `selenium`
- `beautifulsoup4`
- `pandas`
- `openpyxl`
- `undetected_chromedriver`
- `webdriver_manager`

Puedes instalar las librerías necesarias con el siguiente comando:




## ¡Contribuciones Bienvenidas!

Las contribuciones son lo que hacen que la comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. ¡Cualquier contribución que realices es muy apreciada!

Si tienes una sugerencia que pueda mejorar esto, por favor haz un fork del repositorio y crea un pull request. También puedes simplemente abrir un issue con la etiqueta "mejora". ¡No olvides darle una estrella al proyecto! ¡Gracias de nuevo por tu interés y apoyo!

### ¿Cómo Contribuir?

1. Haz un Fork del Proyecto
2. Crea tu Rama de Característica (`git checkout -b feature/1-caracteristica`)
3. Haz tus Cambios (`git commit -m 'Añadir una nueva Característica'`)
4. Haz Push a la Rama (`git push origin feature/Caracteristica`)
5. Abre un Pull Request

## Contacto

- José F. Ramos: joseph0001@gmail.com
- Enlace del Proyecto https://github.com/JRamos84/scraping_python

Si tienes preguntas, comentarios o sugerencias, no dudes en contactarme. Estoy aquí para ayudar y colaborar contigo en cualquier cosa que necesites. ¡Espero saber de ti pronto! 😊

```bash
pip install selenium beautifulsoup4 pandas openpyxl undetected_chromedriver webdriver_manager

