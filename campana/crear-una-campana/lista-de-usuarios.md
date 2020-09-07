---
description: Tercer paso de la creación de una campaña.
---

# Lista de usuarios

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2841%29.png)

Una vez configurada la campaña el siguiente paso es proporcionar a la herramienta la lista de usuarios a la que va a llegar.

Para notificaciones push tienes dos opciones:

1. Enviar una campaña a un segmento de usuarios.
2. Enviar una campaña a usuarios sin sesión activa en la aplicación.

## A un segmento de usuarios

Selecciona la opción **Define audience \(from a file\)**. Crea una lista de usuarios, en formato _.txt_ o _.csv_. Puedes construir la lista en base al número de teléfono, al id de usuario o incluso el email, pero no una combinación de ellos. Selecciona la opción que corresponda en el desplegable **Select token**:

* **MSISDN**. Número de teléfono del usuario. Es muy importante que crees la lista usando el prefijo del país, sin ceros delante, y sin espacios. Solo un número por línea.
* **Email**. Email del usuario, uno por línea.
* **User ID**. Id de usuario. Es muy importante que no añadas texto adicional y que **cada id** de usuario esté **en una línea**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2810%29.png)

Haz clic en **SELECT FILE** para seleccionar el archivo desde tu equipo y subirlo a la herramienta.

![](https://lh4.googleusercontent.com/oFlibCesFIMSdO-idijl79jM6AD85hvL9JdaOJR4LY1iI4EZMjrBkTTKUt9t5TS3jjMmmSv8VFQi-pTTtzAsRLBF6mPfnkw7C3DMkMRFUFgIVMPhIawPFm4L_qKE9NHU0dxFlF32)

Si la lista tiene un formato incorrecto verás un mensaje por pantalla con el aviso. Y si todo es correcto la herramienta te indica que el proceso se ha completado.

![](https://lh6.googleusercontent.com/UTBvbKcNSH7ioVcuQasWswi_OgiO9g_vGJnB_MLnQxepraOrpOfQwtiDlZt7z3BUbKJQzIW8aAPoXoYL46Mm6TJ4Epe7Mt-FtEAkEATm0u3MDYziwitcOouvjnFx0T2ZCy-ldfWh)

{% hint style="info" %}
Si al subir la lista de usuarios el fichero presenta algún identificador que no se corresponde con el tipo seleccionado \(por ejemplo, se incluye un UserID cuando se esperan direcciones de email\), se mostrará un error:
{% endhint %}

```text
There is at least one [userid/ msisdn / email] with a wrong format in your file.
One of them is: "xxxx
```

## A usuarios sin sesión activa

Estas comunicaciones llegan a todos los usuarios que tienen la aplicación instalada en su dispositivo pero que no tienen la sesión activa, por ejemplo, porque no han accedido recientemente o porque han cerrado la aplicación por completo.

Selecciona la opción **Non-logged in users \(no file needed\)**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2836%29.png)

Para definir la audiencia a la que van destinadas estas comunicaciones usa los siguientes filtros \(no obligatorios\):

* **App version**. Versión mínima y versión máxima de la aplicación a la que se enviará la comunicación. Puedes seleccionar las dos versiones \(mínima y máxima\) o solo una versión.
* **Logout date**. Fecha en la que el usuario ha cerrado sesión. Puedes seleccionar desde que fecha \(**From**\) ha cerrado lo sesión o hasta que fecha la ha tenido cerrada \(**To**\). Si quieres enviar la comunicación a usuarios que han tenido la sesión cerrada durante un periodo determinado entonces indica la fecha **From** y la fecha **To**.

{% hint style="info" %}
Esta funcionalidad está disponible para usuarios con una versión de la aplicación 10.8 o superior.
{% endhint %}

* **Operating system**. Sistema operativo. Por defecto se envía a ambos sistemas operativos y por eso está marcada la opción **Any**. También puedes seleccionar **iOS** o seleccionar **Android**.

Haz clic en **UPLOAD** para terminar el proceso de subida de una lista de usuarios.

