# alexa-actions
Skill de Alexa para Home Assistant con idioma Español (es-ES). Derivado de [alexa-actions](https://github.com/keatontaylor/alexa-actions) de [@keatontaylor](https://github.com/keatontaylor).<br>
<br>
![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) Este proyecto amplía el proyecto de [@keatontaylor](https://github.com/keatontaylor) llamado [alexa-actions](https://github.com/keatontaylor/alexa-actions).<br>
El motivo de realizar un proyecto desde cero (no es un fork) es porque Keaton Taylor tiene cerrado todo y no parece responder a peticiones. Es igual. Lo que tiene hecho este usuario es genial.<br>
Para la instalación, por favor, siga los pasos (en un perfecto inglés) que se muestran en su [Wiki](https://github.com/keatontaylor/alexa-actions/wiki) del proyecto [alexa-actions](https://github.com/keatontaylor/alexa-actions) de [@keatontaylor](https://github.com/keatontaylor).<br>
<br>
![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **¡Puedes importar este proyecto como skill de Alexa!**<br>
En el paso en el que puede importar un skill introduzca la URL `https://github.com/fidelbrea/alexa-casa-inteligente` y listo. Esto le ahorrará mucho tiempo.<br>
<br>
![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Consejo**<br>
Puedes simplificar el enlace entre la Skill y Home Assistante usando un token de larga duración.<br>
Cuando se genera el token de larga duración, si el usuario tiene activada la opción de 'solamente acceso desde local', no se autorizará la conexión a través de ese token, por lo que para generar el token de larga duración hay que cumplir dos requisitos: generarlo con una cuenta con perfil de administrador y sin restricciones al acceso únicamente desde local.<br>
<br>
También puedes ahorrarte el dolor de cabeza de trabajar con protocolos de seguridad (HTTPS), o dicho de otra forma, si quieres trabajar con el protocolo HTTP. En este caso deberás usar sí o sí un token de larga duración.<br>
<br>
**¡Advertencia!**<br>
El trabajar con el protocolo HTTP permitirá obtener ese token de larga duración a cualquiera, por lo que no es lo más aconsejable. Ten en cuenta que se podría manipular tu Home Assistant por alguien no deseado. Deberías contar con una clave de una entidad autorizada y trabajar con el protocolo HTTPS. Merece la pena dedicarle un tiempo a informarse sobre el mecanismo de funcionamiento de este protocolo (SSH), conseguir el fichero de clave, ponerlo en tu Home Assistant y añadir unas simples líneas de configuración para tener esa capa de seguridad.<br>
<br>
Si te da pánico lo del protocolo HTTPS o es algo nuevo para ti, busca info sobre:<br>
- HTTPS
- SSL/TLS
- Certificate Authority. Por ejemplo [Let's Encrypt](https://letsencrypt.org/), que es gratis para usuarios modestos.
<br>
...verás que no es para tanto y el beneficio es mucho.<br>
