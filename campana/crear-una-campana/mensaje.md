---
description: Segundo paso de la creación de una campaña.
---

# Mensaje

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2838%29.png)

Selecciona los canales de envío de la comunicación:

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2846%29.png)

Por cada canal que selecciones, se despliegan las opciones de configuración de ese canal.

## Push

Usa este canal para generar notificaciones push.

Rellena los siguientes campos:

* **Title**: representa al remitente de la notificación push. Normalmente es el nombre de la marca \(Tuenti, Movistar, Vivo\). No obstante es criterio de la OB introducir el título/remitente que les parezca adecuado.
* **Url**: enlace donde quieres que apunte la notificación push. Si quieres que la push lleve al usuario a la cuenta añade el _deep link_ que apunte a la cuenta dentro de la app.
* **Push message**: texto de la push. Ten en cuenta que una notificación push debe ser siempre corta ya que el usuario sólo verá el texto que le quepa en la pantalla. Cuando haga clic se le llevará automáticamente a la parte de la app que hayas configurado como URL. Además, los mensajes de las notificaciones se inyectan en el chat, con lo que el usuario las tiene siempre visibles.

  Para iOS no es recomendable que se sobrepasen los 100-120 caracteres y para Android los 50. Este sería el escenario de móviles de gama baja, con pantallas pequeñas.

{% hint style="info" %}
¡Los mensajes push pueden contener _emojis_! 🚀
{% endhint %}

\*\*\*\*💡 **¿Sabías qué?**

Puedes enriquecer los textos de las notificaciones push usando negrita. Para que un texto se vea resaltado escríbelo entre asteriscos \(`*texto*`\).

![As&#xED; se escribe](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/bold_world.gif)

![As&#xED; se ve](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2842%29.png)

Las notificaciones push pueden contener imágenes, animaciones GIF o vídeos. Solo puedes incluir una por notificación y de un solo tipo \(imagen, gif o vídeo\) por cada comunicación.

* **Video URL - Upload a file** 📤: usa este campo para subir un vídeo. Sube también una imagen por si el dispositivo del usuario es antiguo y no permite la reproducción de vídeo.
* **Gif Url - Upload a file**📤: usa este campo para subir un gif. Sube también una imagen por si el dispositivo del usuario es antiguo y no permite la reproducción de GIFs.
* **Picture Url - Upload a file**📤: usa este campo para subir una imagen. Si quieres subir un vídeo o un gif, de forma adicional también tienes que incluir una imagen por si el dispositivo del usuario es antiguo y no es compatible con vídeos o con GIFs.

También puedes subir los recursos \(imágenes, GIFs o vídeos\) desde el menú **Uploads &gt; Upload asset**. Consulta la sección [Subida de recursos: Uploads](../../funcionalidades/subida-de-recursos-uploads.md) para saber más.

{% hint style="info" %}
Ten en cuenta que si tu OB dispone de _zero-rating_, podrá consumir estos vídeos, GIFs o imágenes sin hacer uso de sus datos.
{% endhint %}

{% hint style="warning" %}
Ten en cuenta que los sistemas operativos móviles ofrecen una compatibilidad limitada para vídeos y GIFs:

|  | iOS | Android |
| :--- | :--- | :--- |
| Imagen | ✔︎ | ✔ ︎ |
| GIF | ✔︎ |  |
| Vídeo | ✔︎ |  |
{% endhint %}

* **UTM code**. Código que utiliza Analytics para medir impactos de la comunicación.

{% hint style="danger" %}
No es recomendable que modifiques este campo. Si necesitas hacerlo, consúltalo previamente con el equipo de NOVUM.
{% endhint %}

* **+ADD BUTTON**. Haz clic en el botón para añadir botones a las notificaciones. Puedes añadir uno o dos botones.

  Usa esta funcionalidad para mejorar la experiencia del usuario y aprovechar el impacto del mensaje.

  Rellena los siguientes campos para cada botón:

  * **Button text**. Texto que aparece en el botón de la notificación. Sé breve y usa un texto pequeño. Recuerda que es el nombre de un botón dentro de una notificación _push_.
  * **Button URL**. Enlace donde quieres que apunte el botón. Lo normal es que sea un _deeplink_ distinto al de la propia notificación que estás configurando.
  * **Icon**. En versiones antiguas de Android, icono que puede acompañar al texto del mensaje. En versiones nuevas de Android y en iOS no se muestra el icono aunque lo selecciones.

    🔅 Este campo es obligatorio. Selecciona siempre un icono.

  * **UTM Code**. Se genera automáticamente en función del UTM de la _campaign_.

{% hint style="info" %}
Al final del UTM code, la Comms Tool añade el texto `button1` pero te recomendamos cambiar ese valor por uno descriptivo de la acción del botón. Una buena práctica es que lo llames como el **Button text** pero que en lugar de espacios añadas `_`.

Por ejemplo, si el **Button text** es `Compra el pack`, puedes cambiar el valor del final de la UTM,`button1,` por `compra_el_pack`.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/action_buttons.gif)
{% endhint %}

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/action_buttons.gif)

* **Do a test \(Optional\)**. Si quieres previsualizar cómo le llegará el SMS al usuario indica un número de móvil \(MSISDN\) válido con el prefijo del país pero sin ceros \(por ejemplo, 34666555666\), en el que puedas recibir y visualizar el SMS, y haz clic en **SEND**.

{% hint style="warning" %}
La acción de enviar SMS de prueba es independiente del envío de la comunicación, es decir, aunque hagas clic en **SEND** la comunicación no se envía.
{% endhint %}

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%284%29.png)

## 💡 ¿Sabías que?

Los mensajes que reciben los usuarios a través de notificaciones push también se pueden encontrar en la conversación de soporte. Eso sí, el usuario no puede visualizar los vídeos pero sí las animaciones gif y las imágenes.

