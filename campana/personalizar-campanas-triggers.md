---
description: >-
  Puedes usar un listado de parámetros para personalizar tus campañas y hacerlas
  más interesantes para tus clientes.
---

# Personalizar campañas: triggers

Dentro de la creación de una campaña, es posible personalizarla basándola en _triggers_ \(un disparador de una acción\) a través de unos parámetros determinados. Estos parámetros varían en función del evento que selecciones y la información proporcionada por la API de cada OB.

## Personalizar campañas

1. Selecciona el [canal de envío](../canales-de-envio/) del mensaje. 
2. Para ese canal, en el campo del mensaje, escribe el símbolo `$` en el lugar donde quieras añadir la personalización.  
3. Se abre un desplegable con los parámetros disponibles para el evento. Empieza a escribir el nombre de un parámetro \(están en inglés\) y la herramienta te irá mostrando opciones coincidentes con lo que estás escribiendo.

{% hint style="info" %}
**Ejemplo**

Escribe `name` y la herramienta te mostrará opciones como el`first name`o `last name` del cliente.
{% endhint %}

Una vez enviada la comunicación, el parámetro se reemplazará automáticamente por el valor correspondiente al parámetro que has indicado.

{% hint style="info" %}
Siguiendo el ejemplo: el cliente recibiría una notificación Push en la que leería `Hola Juan.` En el caso improbable en el que esa información no estuviera posible entonces el cliente recibiría un `Hola` y un espacio en blanco.
{% endhint %}

![](https://github.com/iciaparicio/variantes-origen/tree/169a87cd535336e6c183d673fef59f5462c5d585/.gitbook/assets/trigger.gif)

