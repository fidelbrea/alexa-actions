# alexa-actions
Skill de Alexa para Home Assistant con idioma Español (es-ES). Derivado de [alexa-actions](https://github.com/keatontaylor/alexa-actions) de [@keatontaylor](https://github.com/keatontaylor).<br>
<br>
![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) Este proyecto amplía el proyecto de [@keatontaylor](https://github.com/keatontaylor) llamado [alexa-actions](https://github.com/keatontaylor/alexa-actions).<br>
El motivo de realizar un fork es porque Keaton Taylor no implementa el idioma español. No obstante, lo que tiene hecho este usuario es genial. Para la instalación, por favor, siga los pasos (en un perfecto inglés) que se muestran en la [Wiki](https://github.com/keatontaylor/alexa-actions/wiki) del proyecto [alexa-actions](https://github.com/keatontaylor/alexa-actions) de [@keatontaylor](https://github.com/keatontaylor).<br>
<br>
También me gustaría mencionar a [Carlos Cordero](https://github.com/ccorderor), este usuario también ha realizado un fork desde el proyecto de Keaton Taylor que podéis encontrar [aquí](https://github.com/ccorderor/alexa-actions) y lo interesante de [Carlos Cordero](https://github.com/ccorderor) es que tiene el canal de YouTube [Un loco y su tecnología](https://www.youtube.com/@unlocoysutecnologia) dedicado a la domótica. En dicho canal podréis crecer en vuestro proyecto de domótica a través de los consejos y experiencia de Carlos, que no es poca. Es genial contar con gente así. ¡Gracias Carlos!.<br>
(También publica en Instagram, TikTok,...)<br>
<br>
![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **¡Puedes importar este proyecto como skill de Alexa!**<br>
Este repositorio git es una Skill de Amazon, por lo que se puede importar como tal, sólo hay que introducir la URL `https://github.com/fidelbrea/alexa-actions` y listo. Esto le ahorrará mucho tiempo.<br>
Si sigues los pasos de la wiki de K. Taylor encontarás un paso en el que te dice que importes la Skill, si has seleccionado el idioma español no te funcionará con su URL. No te preocupes, usa ésta.<br>
<br>
![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Consejo**<br>
Puedes simplificar el enlace entre la Skill y Home Assistante usando un token de larga duración.<br>
Cuando se genera el token de larga duración, si el usuario tiene activada la opción de 'solamente acceso desde local', no se autorizará la conexión a través de ese token, por lo que para generar el token de larga duración hay que cumplir dos requisitos: generarlo con una cuenta con perfil de administrador y sin restricciones al acceso únicamente desde local.<br>
<br>
También puedes ahorrarte el dolor de cabeza de trabajar con el protocolo de seguridad HTTPS, o dicho de otra forma, si quieres puedes trabajar con el protocolo HTTP. En este caso deberás usar sí o sí un token de larga duración.<br>
<br>
**¡Advertencia!**<br>
El trabajar con el protocolo HTTP permitirá obtener ese token de larga duración a cualquiera, por lo que no es lo más aconsejable. Ten en cuenta que se podría manipular tu Home Assistant por alguien no deseado. Deberías contar con una clave de una entidad CA (Certificate Authority) y trabajar con el protocolo HTTPS. Merece la pena dedicarle un tiempo a informarse sobre el mecanismo de funcionamiento de este protocolo, conseguir el fichero de clave, ponerlo en tu Home Assistant y añadir unas simples líneas de configuración para tener esa capa de seguridad.<br>
<br>
Si te da pánico lo del protocolo HTTPS o es algo nuevo para ti, busca info sobre:<br>
- HTTPS
- SSL/TLS
- Certificate Authority. Por ejemplo [Let's Encrypt](https://letsencrypt.org/), que es gratis para usuarios modestos.
<br>
...verás que no es para tanto y el beneficio es mucho.<br>
