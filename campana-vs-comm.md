---
description: >-
  Sección de Preguntas Frecuentes donde puedes consultar las dudas más
  habituales sobre el uso de la Comms Tool.
---

# FAQ

## **¿Cómo subo una imagen, un vídeo o un GIF a la Comms Tool?**

Accede al menú **Uploads**

Desde **Upload asset** haz clic en **SELECT FILE** y selecciona una imagen desde tu equipo. En ese momento se habilita el botón **UPLOAD**. Haz clic en el botón y copia la URL que se ha generado. Este paso es muy importante dado que esa URL es la que necesitas para poder usar la imagen.

{% hint style="danger" %}
Recuerda que, en el caso de las imágenes, las dimensiones recomendadas son 960x758 px \(aunque se pueden escalar proporcionalmente hasta un máximo de 1440x1137 px\) y su peso máximo 10MB.
{% endhint %}

![](https://lh5.googleusercontent.com/Yjd9gSjRRquz0_Z99rmofUYYOVXavIcg0vHOB5ZWfuGON36jsPi66BjIxNBVit10vKwTtuUwl1qJcxpANORneTFrSK26Jnqmq2B-DDrH9UYvoMmGtDJqgOskd7Jr0BhyaVh5qqty)

{% hint style="info" %}
Necesitas llevar un registro de las URLs generadas por cada imagen que subas dado que no podrás consultar el listado de imágenes desde ningún menú de la Comms Tool. Una buena idea es que tengas una hoja de cálculo donde puedas ir generando una relación de imágenes y su correspondiente URL.
{% endhint %}

¿Necesitas saber más sobre esto? Visita el siguiente artículo:

{% page-ref page="funcionalidades/subida-de-recursos-uploads.md" %}

## **¿Cómo subo un documento a la Comms Tool?**

Accede al menú **Uploads**.

![](https://lh6.googleusercontent.com/aTVGM3GAjimW2JwGDe7lPysVdUYnIEC8poHXFz9gdDC9WO3cZ8i4pO85DCISaLtJ0nx2bmdygfgQskTIoN9pxS7r_TuAzBYL19vtVPMP-TtY1AaOwY1p2YnMOGctP6vltpyUsm3S)

Desde **Upload attachment** haz clic en **SELECT FILE** y selecciona un archivo desde tu equipo. En ese momento se habilita el botón **UPLOAD**. Haz clic en el botón para subir el archivo.

{% hint style="warning" %}
Ten en cuenta el nombre que has puesto al documento porque es el que verá el receptor de la campaña, cuando hagas mención al archivo.
{% endhint %}

![](https://lh4.googleusercontent.com/JOENy8wxL-r-VTH7GPLtR-lqpLk_FYQ5WqBal26b-L_1chegl6zawxDAxD8LdzmdFfjOBhd7i57GJhjAo3dMl-0eBgIiHv47tcerrKMmKFlWwxY8ME3ba8JLNcECAQpFXRFL74lk)

{% hint style="info" %}
**Ejemplo**

Usa la subida de documentos para adjuntar por email un archivo de _Términos y Condiciones_.
{% endhint %}

## **¿Por qué no se ha enviado mi campaña?**

Algunas consideraciones que pueden explicar el problema:

* [x] Comprueba que la campaña no está fuera del horario durante el que no se puede molestar al usuario:

{% page-ref page="campana/crear-una-campana/detalles.md" %}

* [x] Comprueba que el día está dentro del rango de los días durante los cuales se debe enviar 

{% page-ref page="campana/crear-una-campana/detalles.md" %}

* [x] Hay limitaciones en cuanto al ritmo de envío de las campañas, basadas en cuántos usuarios concurrentes puede soportar la aplicación en cada uno de los países. Si para tu país, la limitación es de 2000 mensajes por minuto y has creado dos campañas a más de 5000 usuarios cada una \(por ejemplo\), primero se enviará una campaña \(la más antigua\) a un ritmo de 2000 mensajes por minuto y únicamente tras acabar del todo ese envío se empezará a enviar la segunda campaña.
* [x] Desafortunadamente, los proveedores de email y SMS pueden presentar problemas ocasionalmente. Si la comunicación está marcada en la CommsTool como que ha sido enviada correctamente, contacta con tu proveedor de servicios de envío de email o SMS. Esto solo aplica a estos dos canales. _\*\*_

## No entiendo el estado de la campaña creada

### In progress - Time pause

La campaña ha sido iniciada pero ha entrado fuera de horario sin haber terminado. La comunicación se detiene hasta el siguiente horario disponible \(generalmente la mañana siguiente\).

### In progress - Capacity pause

La campaña ya se ha iniciado pero se ha superado el límite de capacidad de envíos por minuto por lo que se pausa hasta que la capacidad vuelva a liberarse.

### Emergency pause

Se ha producido algún error inesperado. En este caso la comunicación se detiene por motivos de seguridad.

{% hint style="info" %}
**Ejemplo**

A un alto número de usuarios no se les ha podido entregar la comunicación. En este caso esta se detiene por motivos de seguridad.
{% endhint %}

