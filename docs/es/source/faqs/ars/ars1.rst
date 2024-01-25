Puedo sustituir mi mando por un ARS?
=========

Si, si que puedes.

El ARS-USB se diseñó inicialmente para ser conectado al mando original del motor, pero se puede sustituir sin mayores problemas. En el CD-ROM o software de descarga, se incluyen varios esquemas de conexionado a modo de ejemplo. Lo que es importante y hay que tener en cuenta, es que la mayor parte de motores funcionan a 24V, luego vas a necesitar una fuente de alimentación para poder mover el motor. 

Otro detalle, es que algunos motores que funcionan a corriente alterna, emplean un condensador para el arranque y éste suele estar dentro del mando. Al reemplazar el mando original por un ARS-USB, tendrás que poner uno. Este en el caso por ejemplo del HAMIV o T2X.

Otra opción es usar el ARS-USB_Yaesu o ARS-USB_PST pues esos modelos ya están preparados para conectarse con el motor.

Mandos ARS-USB
===============

Desde el año 2020 existen 2 nuevos modelos de ARS-USB que permiten sustituir el mando original por estos nuevos controladores:

 - **ARS-USB_Yaesu:** y que sirve para reemplazar el mando Yaesu en modelos que funcionan a 24Vcc como son: G800, G1000, G2800 o el nuevo G450ADC. Tambien se puede usar para cualquier otro motor que funcione a 24Vcc e incluye todo lo necesario para conectarse y manejar el motor.
 - **ARS-USB_PST:** y que sirve para reemplazar el mando Prosistel de la serie B y D que emplean potenciometro multivuelta y que funcionan a 12 o 24Vcc. Tambien es válido para cualquier motor que emplee potenciometro multivuelta.

Algún relé parece que no funciona
=================================

Muchas veces recibo un correo de un cliente nuevo que me dice que uno de los relés no funciona.
El ARS-USB incluye un mecanismo de protección, para evitar que en algunas situaciones, los relés no se puedan activar. 
Por ejemplo si el ARS lee 0 (o el valor del ADC es el limite izquierdo) entonces el ARS evita e inhibe que el relé de giro a izquierda se pueda activar.

En este enlace se explica el motivo y el por qué:

https://ea4tx.com/faqs/ars-usb-faqs/some-relay-is-not-working/


Reasignar el puerto COM en Windows
=================================

La primera vez que instalas o conectas el ARS al PC, necesitas saber qué puerto COM o serie ha sido asignado por Windows.

Visita este enlace que te explicará como saber el puerto y cómo lo puedes cambiar:

https://ea4tx.com/faqs/ars-usb-faqs/ars-usb-comserial-port