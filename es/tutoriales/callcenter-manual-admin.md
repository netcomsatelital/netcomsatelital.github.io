---
title: Guía de sistema de call center para administradores
article_classname: tutorial1
---

Ingreso y salida del sistema
----------------------------

1. Abra el navegador web (Google Chrome o Mozilla Firefox) e ingrese la siguiente dirección: <https://call.netcomsatelital.com.ar> .

2. Ingrese su nombre de usuario y contraseña.  Presione el botón **Login**.

![Pantalla de ingreso]({{ "/img/es/tutoriales/callcenter-manual-admin/go001.png" | prepend:site.baseurl }})

Una vez identificado, aparecerá la pantalla principal o *dashboard*.  Puede salir del sistema en cualquier momento presionando el botón **LOGOUT** ubicado en la parte superior derecha de la pantalla.

A la izquierda de la pantalla se encuentra la barra de menú, formada por una serie de iconos dispuestos en forma vertical.  Pase el puntero del ratón sobre los diferentes iconos para desplegar los submenúes de cada categoría.

![Pantalla principal]({{ "/img/es/tutoriales/callcenter-manual-admin/go002-mnu_main.png" | prepend:site.baseurl }})

Las categorías son, de arriba a abajo:

- Dashboard
- Telephony
- Admin Settings
- Call Reports
- Recordings
- Support


Ventana de información del usuario
----------------------------------

Para ver información relativa a un agante en particular, ingrese al menú **Telephony** >> **Users**.  Busque el usuario del que desee ver los detalles o escuchar una grabación y presione el icono **i** (color verde) en la columna de la derecha.

![Botón de información de usuario]({{ "/img/es/tutoriales/callcenter-manual-admin/go004-btn_info.png" | prepend:site.baseurl }})

En la nueva ventana, presione sobre el icono del almanaque arriba a la derecha.

![Ventana información de usuario]({{ "/img/es/tutoriales/callcenter-manual-admin/go005.png" | prepend:site.baseurl }})

La búsqueda de registros de ese agente se restringirá a un intervalo de fechas específico.  Para definirlo, haga clic sobre el icono del almanaque de arriba a la derecha de la ventana de información del usuario.  En la nueva ventana que se despliega, primero presione sobre la fecha de inicio del intervalo, y luego presiones sobre la fecha final.  El intervalo especificado quedará resaltado.  Presione el botón **OK**.

![Intervalo de búsqueda]({{ "/img/es/tutoriales/callcenter-manual-admin/go006.png" | prepend:site.baseurl }})

Para volver a la lista de usuarios presiones sobre la **X** en la parte superior derecha de la ventana.


Cómo escuchar grabaciones de las llamadas
-----------------------------------------

Vaya a la **ventana de información del usuario** y seleccione un intervalo de fechas para realizar la búsqueda.  Se mostrará un resumen de las llamadas qwue realizó ese agente en ese intervalo de fechas.  Presiones el enlace **Recordings** (abajo a la izquierda) para desplegar la lista de grabaciones, en donde podrá ver la fecha y hora (columna **Date/Time**) y la duración de la llamada (columna **Seconds**).  Pära escuchar la grabación de una llamada presione sobre el enlace correspondiente en la última columna (**Location**).  Puede hacer clic derecho y seleccionar *Guardar enlace...* para descargar el archivo de audio.

Para volver a la pantalla de información del usuario, presione sobre el enlace **Close** en la parte superior derecha de la ventana.


Cómo ver los horarios cumplidos por un agente
---------------------------------------------

Puede ver los días y horarios en los que un agente se ingresó y salió de la plataforma.  Para hacerlo, vaya a la **ventana de información del usuario**, seleccione un intervalo de fechas y presione sobre el enlace **Agent Login/Logout**.


Cómo ver las llamadas realizadas por un agente
----------------------------------------------

Para ver la lista de llamadas que hizo un agente vaya a la **ventana de información del usuario**, seleccione un intervalo de fechas y presione sobre el enlace **Outbound Calls This Time**.  Presione sobre el enlace **Close** en la parte superior derecha para volver a la pantalla anterior.


Cómo ver los datos recolectados
-------------------------------

En la barra de menú, vaya al menú **Telephony** >> **Lists**.  Busque la lista 998 (**Default Manual List**) y presione sobre el botón de descarga en esa lista (segundo botón de la columna **ACTION**, a la derecha).

![Botón de descarga de lista]({{ "/img/es/tutoriales/callcenter-manual-admin/go007-btn_download.png" | prepend:site.baseurl }})

A continuación se descargará el archivo con los datos actualizados a la fecha, en formato CSV.  Puede abrir ese archivo con una planilla de cálculo como Excel u Open Office.
