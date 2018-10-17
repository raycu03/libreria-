<h1>Introducción al problema</h1>
<p>Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en una sintaxis que favorezca un código legible. Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida, programación funcional. Es un lenguaje interpretado, usa tipado dinámico y es multiplataforma. Python trabajará con un módulo llamado Rx el cual se encargará de la parte reactiva de nuestro programa.
En Rx se derivan Observables utilizando más de 130 operadores disponibles en RxPY.</p>

Cada operador producirá un nuevo Observable que transforma las emisiones de la fuente de alguna manera. Por ejemplo, podemos usar map() para cada String a su longitud, luego filter() para longitudes que sean al menos 5. Esto dará como resultado dos Observables separados construidos unos de otros.
Flask es un framework minimalista escrito en Python que permite crear aplicaciones web rápidamente y con un mínimo número de líneas de código. Está basado en la especificación WSGI de Werkzeug y el motor de templates Jinja2 y tiene una licencia BSD
<h1>Problema o situación</h1>
Consiste en un sistema que simula el comportamiento de préstamo de libros en una biblioteca
<h1>Proceso de solución</h1>
<p><b>Paso 1:</b> En el navegador de su preferencia descargar Python en el sitio oficial y realizar la configuración recomendada. Para su facilidad le brindaremos un proceso de guía para instalación en Windows.
Enlace1: https://www.python.org/downloads/windows/</p>
<p><b>Paso 2:</b> En el proceso de instalación es importante agregar la ruta en el PATH de ruta en Windows.</p>
<p><b>Paso 3:</b> Luego de la correcta instalación de Python, acceder al cmd en modo administrador para instalar pip.
Enlace 2:https://recursospython.com/guias-y-manuales/instalacion-y-utilizacion-de-pip-en-windows-linux-y-os-x/</p>
<p><b>Paso 4:</b> Al instalar el pip podrás instalar los módulos de Python que necesites, entre esos módulos se encuentra Rx.
Enlace3: https://programminghistorian.org/es/lecciones/instalar-modulos-python-pip</p>
<p><b>Paso 5:</b> Se realiza primero la programación de los métodos en Python con Rx.</p>
<p><b>Paso 6:</b> Se revisará la documentación de flask para que los programas hechos puedan visualizarse en la web. Aquí es importante el llamado a los métodos. 
<p><b>Nota: </b> Para instalar todos los modulos necesarios para la correcta ejecucion del programa, moverse en la consola hasta la carpeta y ejecutar el comando:
pip install -r requirements.txt</p>
