---
description: Primer paso de creación de una campaña.
---

# Detalles

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2821%29.png)

Rellena los campos según tus necesidades. Desde esta sección indica el nombre de la campaña y completa los datos referentes a la programación del envío.

![](https://lh4.googleusercontent.com/P3MXH2HppwpLH9MMt4TJoT9VdYP3EhhpS-_wuvuC88iHjYu2NQeTOmcWbrYnwzY4pBQbl81qCKez2sgADr4y5yfHpckLUY2mLlPv1LjA0J1kaPrh33fB0py9l1RfpW7VIkLgT3la)

* **Title**. Título de la campaña. Este título no lo ven los usuarios. Es una forma que tienes internamente de identificar la campaña que estás configurando y también te resultará muy útil para poder identificar la campaña en Analytics.
* **Campaign Type**. Selecciona el tipo de comunicación que estás creando.
  * **Service**. Comunicaciones relacionadas con el propio servicio de telecomunicaciones o servicios en general. La peculiaridad de las comunicaciones de este tipo _Service_ es que llegan siempre al usuario, independientemente de cómo el usuario haya configurado la recepción de notificaciones.
  * **Marketing**. Comunicaciones comerciales que solo llegan al usuario si tiene activada \(desde _Ajustes  &gt; Notificaciones_ de la app\) la recepción de comunicaciones comerciales. No todas las OBs tienen opción de desactivar esta opción en cuyo caso les llegan siempre todas las notificaciones.

{% hint style="danger" %}
No es recomendable que modifiques este campo. Si necesitas hacerlo, consúltalo previamente con el equipo de NOVUM.
{% endhint %}

* **Campaign delivery schedule**. Selecciona si la activación de la comunicación es manual o la vas a programar para un momento concreto.
  * **Manual activation**. Usa la opción de envío manual para enviar la comunicación en el momento, es decir, cuando crees la comunicación y hagas clic en **SEND**.
  * **Schedule campaign delivery**. Usa la opción de programación de una comunicación para enviarla en un momento diferente al de creación. Es muy útil, por ejemplo, para lanzar una comunicación sobre un cambio de tarifas cuando sabes el día exacto que eso va a pasar. En general, está pensado para no enviar la comunicación en el mismo instante.

    Si seleccionas esta opción se despliega un menú para que indiques cuándo lanzar la comunicación: Indica el día de comienzo, la hora y los minutos.

![](https://lh3.googleusercontent.com/u86ceruPQeAWH8AdbAnljKnvYGlLaY-fPrBSptYfStgj-NFT4HQhoZxosJEQEhGgwLe5M0dYm8LsbHW7G1Sn9-AX-wDLhGYFzYeSeGevAOrZQ2NAQDQ5ccwk0SzPWth1lgFhTmlQ)

* **Delivery will take place on**. Con independencia de que hayas seleccionado una campaña manual o programada hay restricciones en cuanto a cuándo se envía una campaña. Por defecto, está desactivado el envío de comunicaciones los sábados y domingos, y el horario entre las 21 horas y las 9 horas todos los días. Puedes seleccionar qué días sí se puede enviar una comunicación y qué días no, seleccionándolos.

  También puedes seleccionar los intervalos en los que se puede enviar la comunicación y la zona horaria, para que no tengas que calcular la diferencia horaria ni tener en cuenta desde qué país creas la comunicación.

{% hint style="info" %}
**Ejemplo**

Alice selecciona envío manual de una comunicación y termina de crearla el viernes a las 18:34 horas.

Su configuración de envío es que no se envíe ni viernes, ni sábado, ni domingo. Como rango horario, dentro de la zona horaria Europe/Madrid, de 9:00 a 21:00 horas.

Eso significa que la comunicación no se enviará hasta el lunes a las 9:00 de la mañana, pese a que era una configuración manual y la realizó un viernes.
{% endhint %}

* **Comms per minute**. Velocidad de envío de la comunicación, es decir, cuántas comunicaciones se envían por minuto. En función de la configuración para la OB, el número mínimo y el número máximo de envíos por minuto varía.

{% hint style="warning" %}
Si has configurado más de una comunicación a la vez, es decir, que las comunicaciones estén configuradas para enviarse al mismo tiempo, ten en cuenta que las comunicaciones enviadas por minuto son las totales. Es decir, no pongas el máximo valor de **Comms per minute** en todas las comunicaciones porque entonces se producirá un colapso y por tanto habrá error con los envíos e incluso una caída del servicio de la app.
{% endhint %}

![](https://lh4.googleusercontent.com/DyGphgkFJans51A2fOU1NLrQgeS1vKt3Kcj228Qeu_CscE4nh9hgkLdxieWCmLrT748OXOpW92Ms9tMcDkOAcE4pnoOAbBXE39z7dudG_MeeRmiEAIWg6pBUg_8QDmOJcW9Qbvsh)

{% hint style="info" %}
**Ejemplo**

Alice configura dos comunicaciones, _Comunicación1_ y _Comunicación2_, que van a enviarse a la vez. Quiere que se envíen las máximas posibles por minuto. En el caso de su OB el máximo de _comms_ por minuto es de 300:

Para ello configura 150 comunicaciones por minuto en la _Comunicación1_ y 150 comunicaciones por minuto en la _Comunicación2_.

En total, son 300 comunicaciones por minuto, el máximo permitido \(para su OB\).

¡El envío se realiza correctamente!
{% endhint %}

Haz clic en **NEXT** \(en la parte inferior derecha\) para continuar y que se guarden los cambios. Para salir de la configuración haz clic en **CANCEL** \(parte superior derecha\), pero ten en cuenta que, si sales de la configuración en este momento, la comunicación no se guardará.

