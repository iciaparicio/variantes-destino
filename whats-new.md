---
description: Asegúrate de no perderte nada. Esto es lo último que hemos hecho.
---

# ¿Aún no te has enterado?

## 28 de julio de 2020

### ⏱ Gestión de comms en horas de "no molestar"

El envío de notificaciones a los usuarios es un tema muy cuidado por los equipos de Marketing y de Producto. ¡Qué importante es "no molestar" a nuestros clientes! Pero no debemos tampoco tener miedo a contarles nuestras últimas novedades, darles información relevante o aprovechar a realizar campañas interesantes para poner en valor nuestro producto.

Conscientes de ese impacto, podemos configurar las notificaciones para que no se envíen en determinados momentos que podemos considerar que "molestan" a los clientes.

![](https://media.giphy.com/media/1guRIRC4vCtf5zr03ss/giphy.gif)

Pero hasta ahora, si una comm se generaba dentro de esas horas excluidas, lo que sucedía es que se enviaba pasado ese intervalo.

Podía darse el caso de que, pasado el intervalo, la comm ya no tuviera sentido. Por eso, hemos añadido la posibilidad de que puedas decidir qué hacer con la notificación:

* **Enviarla igualmente**, en cuanto sea posible pasado el intervalo de "no molestar"
* **No enviarla**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/exclude_hours.png)

Consulta todo el detalle de cómo hacer esta configuración 👇

{% page-ref page="trigger-comms/crear-una-comm/detalles.md" %}

### 🧹 Actualizados los tipos de notificaciones en las campañas

Pese a que la Comms Tool te permite enviar campañas por diferentes medios hemos "limpiado" nuestra guía de uso poniendo foco en el medio que realmente usan todas las OBs: las **push notifications**.

Contenido más claro, más limpio y más centrado.

{% page-ref page="campana/crear-una-campana/mensaje.md" %}

## 10 de diciembre de 2019

### 🖲️Action buttons en notificaciones push

¡Ahora las notificaciones Push son más interactivas que nunca! Puedes incluir uno o dos botones de acción para mejorar la experiencia del usuario y aprovechar el impacto del mensaje.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/action_buttons_mobile.png)

Cada botón lleva su propio enlace que, en condiciones normales, es que sea diferente al de la propia notificación push, con el fin de guiar al usuario a realizar una acción más concreta.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/action_buttons.gif)

Por ejemplo, imagina que estás creando una notificación push para avisar al usuario de la app que dispone de nuevos terminales en oferta pero quieres enseñarle uno en particular, el terminal _TheBest_ que acaba de salir, y pretendes que lo compre.

En este caso sigue los siguientes pasos:

1. Configura la notificación push para que lleve al usuario al portal de terminales.
2. Configura el botón 1 para que lleve al usuario al proceso de compra del terminal _TheBest_.

Si el usuario hace clic en cualquier lugar de la notificación push que no sea el botón irá a la tienda de terminales.

Si el usuario hace clic en el botón 1, accederá directamente a la opción de compra del terminal _TheBest_.

**¿Cómo lo hago desde la Comms Tool?**

Mira cómo configurar Actions Buttons para una _trigger comms_ \(en el apartado de **Push** puedes consultar la sección **ADD BUTTON** para conocer en detalle cómo configurar una _trigger comm_ para añadirle botones.\)👇

{% page-ref page="trigger-comms/crear-una-comm/mensajes.md" %}

Mira cómo configurar Actions Buttons para una _campaign_ \(En el apartado de **Push** puedes consultar la sección **ADD BUTTON** para conocer en detalle cómo configurar una _campaign_ para añadirle botones.\)👇

{% page-ref page="campana/crear-una-campana/mensaje.md" %}

#### 🔦 Consulta la versión de la Comms Tool

¿Aún no tienes claro qué **versión de la Comms Tool** estás usando? No te preocupes porque ya la puedes consultar desde la propia herramienta.

Echa un vistazo en la parte inferior izquierda de la Comms Tool. A medida que salgan nuevas funcionalidades que solo apliquen a partir de una determinada versión, podrás ver en esa parte cuál es tu versión de la herramienta y saber así si dispones o no de la funcionalidad en cuestión.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/version_comms_tool_01.png)

![](https://media.giphy.com/media/Ti7zzdphAacCXpJPWm/source.gif)

## 16 de octubre de 2019

### 📈 Nuevo reporte de comms

¿Quieres saber si tu _triggered comm_ está funcionando? ¿Qué impacto está teniendo? ¿Cuántos usuarios no han podido recibir la comunicación? A partir de ahora tienes esta información a tu disposición en el reporte de la comunicación.

#### ¿Qué tipo de información puedo ver?

Por ejemplo, cuántos mensajes no se han podido entregar porque el usuario ha desinstalado la aplicación o el impacto por sistema operativo \(iOS vs Android\). Además, ¡podrás consultar en el gráfico estos estados para cada uno de los días del último mes!

🎯 Consulta la relación de eventos que indican el estado del envío:

{% page-ref page="campana/estados-de-una-campana/eventos.md" %}

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/new-reports.gif)

### 🤠 Personaliza las _triggereds comms_

Entrega el mensaje correcto en el momento adecuado, donde los usuarios lo esperan.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/triggered_news.gif)

🎯 ¿Quieres saber cómo hacerlo? Esto te interesa:

{% page-ref page="campana/personalizar-campanas-triggers.md" %}

### 💄 Texto enriquecido en las notificaciones PUSH

Ya puedes enviar comunicaciones _Push_ a través de CommsTool enriqueciendo el texto con el uso de la negrita.

#### ¿Cómo lo hago?

Dentro del campo **Push message** Escribe, entre asteriscos, el texto que quieres poner en negrita:

![As&#xED; se escribe](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/bold_world.gif)

![As&#xED; se visualiza](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2842%29.png)

{% hint style="info" %}
El texto enriquecido sólo se visualiza en dispositivos con sistema operativo Android. Para iOS el texto se ve normal, sin enriquecer.
{% endhint %}

