ej: crear un issue y que me llegue un mensaje a discord
 
[] Integracion github con discord

Crear servidor discord propio
Crear canal de texto propio

En los settings de canal de texto -> Integraciones
Ver Webhooks -> Nuevo Webhook -> seleccionamos Nombre y canal y copiamos la URL del webhook

Volvemos al repositorio de github
Settings -> Webhooks -> add Webhook
en 'PayLoad URL' pegamos el enlace de discord y añadimos '/github'

SSL verification dejar activado
Which events would you like to trigger this webhook?
- Cuando se haga un push
- Todo
- Especificar lo que quiero que se mande (pinchamos en issues por ejemplo)
