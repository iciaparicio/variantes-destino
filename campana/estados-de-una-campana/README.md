---
description: Conoce los diferentes estados que puede tener una campaña.
---

# Estados de una campaña

Desde el menú principal de **Campaigns** dispones del listado de todas las campañas creadas. En la parte derecha puedes ver el estado en el que se encuentra cada una.

![](https://lh4.googleusercontent.com/XclH5dCR6sXqN8Xrxe7npzIGd3nmBapuAuwQTt9BBuR7xitn9bi-wawrowhopL_w_k4xyqkQRXeFLNO_nlPMbxZnRCiZPYsxOSKTuA07HIep0EhPeluZ0Et0tvcP3Y4uPatqtss4)

Una campaña puede tener los siguientes estados:

## Pendiente de activación

En la columna **STATUS** la campaña está como **PENDING ACTIVATION**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2817%29.png)

La campaña aún no está creada completamente. Puede haber datos sin añadir o simplemente aún no se quiere enviar.

Desde el listado de campañas, haz clic en la línea de la campaña para terminar de añadir los datos que faltan o para enviarla, sin aún estaba pendiente por algún motivo.

![](https://lh3.googleusercontent.com/bNxhGxoRDricRspO7joonHohwhP6wZV_ZNgYEGMLygvOrzdIhNXAz8FdVPWnZtNQiiSEh5UNL2R4uGgtSIHWUfhL7EbEsbVU_b1wAMdHDpMhZkYdcx8v1-1qxQ8PN7G1Jv7zvErN)

## Enviando

En la columna **STATUS** la campaña está como **SENDING**.

La campaña está siendo enviada en ese momento. Dispones de la opción de pararla en caso de que sea necesario.

## Pausada

En la columna **STATUS** la campaña está como **PAUSED**.

La campaña se ha parado mientras estaba siendo enviada. Esto puede suceder por dos motivos:

1. Que decidas parar el envío por el motivo que consideres.
2. Que la Comms Tool pause el envío de una o varias campañas que provoquen que el límite de envío se supere. 

{% hint style="warning" %}
El límite de envío varía según la OB.
{% endhint %}

En cuanto una campaña en curso termina se reanuda el envío de la campaña o campañas pausadas.

{% hint style="info" %}
**Ejemplo**

Alice quiere enviar tres campañas a la vez a 9k/min en Brasil. Como la capacidad de las campañas supera el límite de capacidad, una de ellas se parará automáticamente.

Una vez que una de las campañas en curso termine de enviarse, la que se ha quedado pausada se reanudará de manera automática.
{% endhint %}

## Completada

En la columna **STATUS** la campaña está como **COMPLETE**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2829%29.png)

El envío de la campaña está completado, es decir, la campaña ha sido enviada a todos los usuarios seleccionados.

Desde el listado de campañas, haz clic en la línea de la campaña para acceder a los datos de la campaña enviada.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2816%29.png)

## Cancelada

En la columna **STATUS** la campaña está como **CANCELLED**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2837%29.png)

Desde el listado de campañas, haz clic en la línea de la campaña para acceder al detalle de la campaña. Haz clic en **CANCEL**.

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/image%20%2833%29.png)

Si cancelas una campaña, se haya empezado a enviar o no, se marcará como **CANCELLED**. Una vez cancelada no puedes reiniciar la campaña. Esta opción está desarrollada para campañas que se crearon por error o que contienen errores.

Para borrar la campaña haz clic en **DELETE**. Cuando lo hagas la campaña desaparecerá de la lista de campañas.

🎯 Amplía la información sobre la r**elación de eventos que indican el estado** del envío:

{% page-ref page="eventos.md" %}

