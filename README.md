# PrimeraWebDjango
Desafío guiado - Aplicación de web en Python
● Para realizar este desafío debes haber estudiado previamente todo el material
disponible en el LMS correspondiente a la unidad.
● Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los
requerimientos solicitados y sube el .zip en el LMS.
● Desarrollo desafío: Individual
● Puntaje total: 10 puntos.
● Tiempo desarrollo: 90 a 120 minutos
● Para la realización del desafío deberás tener instalado en tu sistema operativo las
siguientes herramientas y programas utilitarios: python, pip y virtualenvwrapper
Descripción
Un cliente nos solicita una aplicación web donde tenga la vista Home, About y Contact. En
este sentido, la solución es entregarle un ejemplo utilizando Django. Para los contenidos de
las vistas se pueden entregar textos de prueba generados con Lorem Ipsum.
En el caso de la vista contact, se sugiere implementar un mini formulario de contacto con
HTML.
Tips: Las urls quedarían de la siguiente forma:
from holaMundo.views import home,about, contact
urlpatterns = [
path('admin/', admin.site.urls),
path('', home),
path('about/', about),
path('contact/', contact)
]
¡Importante! Las versiones utilizadas para este desafío, son para intencionar que
es posible tener, en un mismo proyecto de Django, múltiples aplicaciones y que
estas respondan a versiones distintas. Para obtener información de las últimas
versiones de Django, puedes consultar la documentación oficial.
_ 1
www.desafiolatam.com
Requerimientos
1. Crea la vista para el Home de la aplicación.
(3 Puntos)
2. Crea la vista para el About de la aplicación.
(3 Puntos)
3. Crea la vista para el Contact de la aplicación y posee un mini formulario de contacto
para ejemplificarle al cliente el resultado.
(4 Puntos)
¡Mucho éxito!
Consideraciones y recomendaciones
Para la realización del desafío deberás tener instalado en tu sistema operativo las
siguientes herramientas y programas utilitarios: python, pip y virtualenvwrapper.