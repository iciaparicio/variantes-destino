---
description: Primer paso de creación de una 'trigger comm'.
---

# Detalles

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2824%29.png)

Rellena los campos según tus necesidades. Desde esta sección indica el nombre de la _trigger comm_ y completa los datos referentes al evento que dispara la comunicación.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/detalle_triggers.png)

* **Title**. Título de la _trigger comm_. Este título no lo ven los usuarios. Es una forma que tienes internamente de identificar la _comm_ que estás configurando y también te resultará muy útil para poder identificar la campaña en Analytics.
* **Description**. Descripción breve de la _trigger comm_. Usa este campo para definir cuál es el objetivo de la _trigger comm_, a quién va dirigida y ten en cuenta que esta descripción te puede ayudar a identificar la _comm_ fácilmente. 
* **Comm type**. Selecciona el tipo de _trigger comm_ que estás creando.
  * **Service**. _Comms_ relacionadas con el propio servicio de telecomunicaciones o servicios en general. La peculiaridad de las comms de este tipo _Service_ es que llegan siempre al usuario, independientemente de cómo el usuario haya configurado la recepción de notificaciones.
  * **Marketing**. _Comms_ comerciales que solo llegan al usuario si tiene activada \(desde _Ajustes &gt; Notificaciones_ de la app\) la recepción de comunicaciones comerciales. No todas las OBs tienen opción de desactivar esta opción en cuyo caso les llegan siempre todas las notificaciones.

{% hint style="danger" %}
No es recomendable que modifiques este campo. Si necesitas hacerlo, consúltalo previamente con el equipo de NOVUM.
{% endhint %}

* **Tags**. Selecciona en el desplegable la etiqueta o las etiquetas para identificar fácilmente la _trigger comm_.

  Si necesitas crear etiquetas nuevas contacta con tu administrador.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%289%29.png)

* **Event**. Selecciona en el desplegable el evento que provoca el envío de la _trigger comm_.
* **Delivery delay for the Comm**. Selecciona los minutos \(**Minutes**\), las horas \(**Hours**\) o los días \(**Days**\) que tienen que pasar para que se envíe la _comm_ una vez que se produce el evento. Usa esta opción si no quieres que la _trigger_ comm se envíe exactamente en el momento en que se produce el evento que la desencadena.

{% hint style="info" %}
**Ejemplo**

Alice está configurando un mensaje de Onboarding para que el usuario que abra la app por primera vez pueda leerlo. Pero Alice quiere que ese mensaje se muestre a los dos días del primer acceso del usuario.

Para eso Alice rellena el campo **Delivery delay form the Comm** y en el campo **Days** indica _2_.
{% endhint %}

* **Exclude hours**. Indica el intervalo del día en que, con independencia del _trigger_ que lanza la _comm_ o el _Delivery delay_, al usuario no le llegará ninguna notificación. Es, por tanto, el intervalo en el que "no se molesta" al usuario.
  * **No**. Marca esta opción para no indicar horas excluidas.
  * **Yes**. Marca esta opción para indicar en qué intervalo de horas no quieres que lleguen notificaciones. Si marcas esta opción entonces se muestran los siguientes campos:

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/yes_exclude_hous%20%281%29.png)

* **Start hour**. Hora a la que comienza el intervalo de "no molestar".
* **End hour**. Hora a la que finaliza el intervalo de "no molestar".
* **Time zone**. Zona horaria en la que se lanzará la _trigger comm_.
* **If comm generated during exclude hours**. Selecciona qué hacer con la comm si, por el motivo que sea, se genera durante las horas de "no molestar":
  * **Send it in the next available slot**. Para enviar la _comm_ cuando se termine el intervalo de "no molestar". 
  * **Discard**. Descartar la _comm_ si se se genera dentro del intervalo de "no molestar" y por tanto no enviar esa _comm_.

