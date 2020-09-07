---
description: Definición formal de los estados de una campaña en relación con los eventos .
---

# Eventos

## Eventos para _triggered comms_

En campañas activas puedes consultar una relación de eventos que indican el estado del envío \(por ejemplo, _push received_, que indica si una push ha sido recibida por el usuario\).

<table>
  <thead>
    <tr>
      <th style="text-align:left">Event name</th>
      <th style="text-align:left">Affects</th>
      <th style="text-align:left">Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Composition error (fail retrieving user info)</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">The message to send could not be composed. For instance, a variable in
        the message could not be replaced by the value because this value was not
        found.</td>
    </tr>
    <tr>
      <td style="text-align:left">Generated messages</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">The comm copies and media have been composed, ready to be delivered</td>
    </tr>
    <tr>
      <td style="text-align:left">Message composition errors (segmentation failed)</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Error generating the comm, there is some problem in the comm conditions
        configuration</td>
    </tr>
    <tr>
      <td style="text-align:left">Message composition errors (invalid user information)</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">There is invalid data in the generated comm (EG. Sending a user name in
        the msisdn field).</td>
    </tr>
    <tr>
      <td style="text-align:left">Non-delivered (testing purposes)</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Used for test purposes. The comm is generated but not delivered.</td>
    </tr>
    <tr>
      <td style="text-align:left">User not recognized</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">The message cannot be sent to this specific user (EG. Sending a push to
        an msisdn without a linked user).</td>
    </tr>
    <tr>
      <td style="text-align:left">Chat messages failed</td>
      <td style="text-align:left">Chat messages/ Survey/Chat Bot</td>
      <td style="text-align:left">Internal error sending chat messages to the user.</td>
    </tr>
    <tr>
      <td style="text-align:left">Push received (Android)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">Push has been received in the Android phone (the icon can be seen in top
        of the screen)</td>
    </tr>
    <tr>
      <td style="text-align:left">Push open (Android)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">When user taps on push icon in Android device</td>
    </tr>
    <tr>
      <td style="text-align:left">Dispatched by Novum</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">When the comm has been sent from Novum systems (not necessarily received
        by final user)</td>
    </tr>
    <tr>
      <td style="text-align:left">SMS fallback failed</td>
      <td style="text-align:left">Fallback Sms</td>
      <td style="text-align:left">Fallback sms delivery (for unread push) has failed</td>
    </tr>
    <tr>
      <td style="text-align:left">Blacklist</td>
      <td style="text-align:left">Sms/Email</td>
      <td style="text-align:left">Comm delivery has been discarded because the user is blacklisted</td>
    </tr>
    <tr>
      <td style="text-align:left">Spam prevention</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Comm that has not been sent to a user to avoid spam (for chat messages:
        same comm sent more than once in 15 min; for other types: same comm sent
        more than 5 times in one day)</td>
    </tr>
    <tr>
      <td style="text-align:left">Fallback comm spam prevention</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Similar to SENT_SKIPPED_BY_RATE_LIMIT. Fallback comm that has not been
        sent to a user to avoid spam (same comm sent more than once in 15 min)</td>
    </tr>
    <tr>
      <td style="text-align:left">Opt-out marketing comms</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">The comm was not sent because the user disabled the option to receive
        marketing comms.</td>
    </tr>
    <tr>
      <td style="text-align:left">Service delivery error</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Fallback SMS dispatched by Novum</td>
      <td style="text-align:left">Fallback SMS</td>
      <td style="text-align:left">When the fallback comm has been sent from Novum systems (not necessarily
        received by final user)</td>
    </tr>
    <tr>
      <td style="text-align:left">Unknown delivery error</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Comm delivery has failed for an unspecified reason</td>
    </tr>
    <tr>
      <td style="text-align:left">Fallback SMS unsent</td>
      <td style="text-align:left">Fallback SMS</td>
      <td style="text-align:left">The first sms message has succeeded, so it was not necessary to send the
        fallback.</td>
    </tr>
    <tr>
      <td style="text-align:left">Push open (iOS)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">When user taps on push icon in iOS device</td>
    </tr>
    <tr>
      <td style="text-align:left">Chat messages delivered</td>
      <td style="text-align:left">
        <p>Chat messages/</p>
        <p>Survey/Chat Bot</p>
      </td>
      <td style="text-align:left">Chat messages successfully sent to the user.</td>
    </tr>
    <tr>
      <td style="text-align:left">Addressing failure</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">Error getting info about the receiver (can be an internal error an for
        unknown reason, or an error because an invalid receiver in the event/mass-comm)</td>
    </tr>
    <tr>
      <td style="text-align:left">Opt-out service comms</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">The comm was not sent because the user disabled the option to receive
        service comms.</td>
    </tr>
    <tr>
      <td style="text-align:left">Push received (OS unknown)</td>
      <td style="text-align:left"><b>Push</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Receiver not found</td>
      <td style="text-align:left">All</td>
      <td style="text-align:left">When fails to render the receiver field of the comm. The most probable
        cause is that it can&#x2019;t get the receiver data from the input data.</td>
    </tr>
    <tr>
      <td style="text-align:left">No devices found</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">The receiver has not devices logged that can receive the push.</td>
    </tr>
    <tr>
      <td style="text-align:left">Push delivered (Android)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">Google has informed us that the push has been delivered to the device.</td>
    </tr>
    <tr>
      <td style="text-align:left">Uninstalled or logged-out devices (Android)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">Google informed us that the token we have to send a push to a delivery
        it&#x2019;s invalid.</td>
    </tr>
    <tr>
      <td style="text-align:left">Uninstalled or logged-out devices (iOS)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">Apple informed us that the token we have to send a push to a delivery
        it&#x2019;s invalid.</td>
    </tr>
    <tr>
      <td style="text-align:left">Comm sent, message not injected</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left">The push has been sent, but the chat injection has failed.</td>
    </tr>
    <tr>
      <td style="text-align:left">Discarded fallback (blacklist)</td>
      <td style="text-align:left">Fallback SMS</td>
      <td style="text-align:left">Msisdn for the sms It&#x2019;s in the blacklist.</td>
    </tr>
    <tr>
      <td style="text-align:left">Push delivered (OS unknown)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Push open (OS unknown)</td>
      <td style="text-align:left">Push</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

