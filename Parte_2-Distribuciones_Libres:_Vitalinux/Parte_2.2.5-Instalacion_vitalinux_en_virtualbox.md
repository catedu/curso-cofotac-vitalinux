## Instalación de Vitalinux en Virtualbox

En este apartado del curso se va a presentar a el afamado y potente software __VirtualBox__ que nos va a permitir poder probar y testear el sistema operativo que deseemos, además de poder instalar sobre él las aplicaciones que nos interesen pudiendo trabajar con ellas de igual forma a como lo haríamos si las tuvieramos instaladas en nuestro equipo físico.

**Virtualbox** es la herramienta ideal para la realización de pruebas y test de sistemas operativos. Se trata de una aplicación software de Escritorio que nos permite instalar y probar sistemas operativos sin afectar en absoluto al sistema operativo que tenga instalado el equipo físico.

Tal cómo lo definen en su página oficial _"***VirtualBox*** es un poderoso software de virtualización tanto para la empresa,  como para el uso doméstico. Además se caracteriza por ser la única solución profesional que está libremente disponible como software de código abierto bajo los términos de la Licencia Pública General de GNU (GPL v2)_".

En definitiva, **VirtualBox** es un software muy interesante que nos va a permitir crear una máquina virtual, para posteriormente sobre ésta instalar y probar un sistema operativo (*p.e. Vitalinux*) y todas sus aplicaciones obteniendo como resultado exactamente lo mismo que si lo hubiéramos hecho directamente sobre el equipo físicamente.

{% notificacion_important title='¿Qué significa que la máquina es Virtual?' %}
<b>Virtualbox</b> nos va a permitir crear máquinas virtuales en un sentido metáforico, ya que cuando creamos una máquina en Virtualbox en realidad estamos cediendo parte de los recursos hardware de la máquina física a la máquina creada.  Es decir, a modo de ejemplo, si disponemos de un equipo físico con 4GB de memoria RAM y creamos una máquina en Virtualbox con 1GB de memoria RAM, ese GigaByte es real (<i>no es virtual</i>) ya que se los esta <b>quitando a la máquina física</b> dejándola únicamente con 3GB.  Entendido lo que sucede con la memoria RAM de la máquina virtual, exáctamente igual podríamos decir de la CPU, la tarjeta de sonido, las tarjetas de red, etc ...  Por tanto, Virtualbox es un software que tiene la capacidad de hacernos creer que tenemos varias máquinas en una.
{% endnotificacion_important %}

Crear una máquina virtual es tan facil como seleccionar la acción de Nueva Máquina Virtual, y seguir los pasos que se indican en el asistente. Si dejamos todo por defecto no tendremos problemas, pero por revisar:

-  **Nombre y Tipo de máquina**. Nombre deseado y tipo Linux (32 o 64, según deseemos)
-  Memoria **RAM** que le asignamos (1GB por ejemplo está bien)
-  Crear un **disco** Virtual (se recomienda cuando lo pida reservar el espacio dinámicamente para que solo ocupe en disco el espacio que gastemos). El tamaño del disco debe ser **superior a 25 GB** para no tener problemas de espacio

Una vez creada la máquina virtual, tendremos que ir a su configuración e indicar la ruta de la ISO de Vitalinux para posteriormente ya arrancarla.

Con la finalidad de tratar que sea más comprensible el **proceso de creación de una máquina Virtual en Virtualbox** se ha creado el siguiente videotutorial (*advertir que este videotutorial se realizó para el curso de Aularagon de Vitalinux, por lo que las referencias a dicho curso habrá que omitirlas):*

{% youtube %}https://youtu.be/NsVrwUFeYrc{% endyoutube %}


