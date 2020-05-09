<<<<<<< HEAD
# web_scraping
Para descargar imágenes cuando el volumen es muy alto
=======
### Web_scraping

Descarga imágenes cuando el volúmen es muy alto

#### Objetivo.
Ayudar a realizar la descarga de grandes volúmenes de imágenes para galerias, para uso en machine learning, deep learning etc.


Actualmente funciona para páginas donde las imágenes se encuentran enumeradas en secuencia ejemplo /1, /2, /3 ...

Tiene para manejar un rango para controlar la cantidad de imágenes a descargar.

`for i in range(1, 6):`

Se puede cambiar la página de descarga en la siguiente línea de código.

`response = requests.get('https://xkcd.com/{}'.format(i))`


Importante verificar que la página de donde se quiera descargar tenga bien establecido en el HTML---> img señalando las imágenes, ya que algunas veces las definen diferente
>>>>>>> e2638e25301ea6482a215a9a02afbef2e4836315
