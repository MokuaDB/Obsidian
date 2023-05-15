___

## *Denegación de Servicio (DoS)*


Un ataque de denegación de servicio busca privar a los usuarios el acceso a su red o equipo. Normalmente busca la pérdida de la conectividad con la red donde se encuentran estos recursos, bien por un consumo excesivo del ancho de banda o sobrecarga del sistema atacado. 
Un tipo de ataque en el que se produce un desbordamiento de búfer de la memoria puede hacer que una máquina consuma todo el espacio disponible en el disco duro, la memoria o el tiempo de la CPU.

##### Tipos de ataque

- Ataque Smurf: un ataque DoS en el que un actor malicioso utiliza la dirección de difusión de una red vulnerable mediante envío de paquetes falsos, lo que resulta en la inundación de una dirección IP objetivo.
- Inundación de Ping: este sencillo ataque de denegación de servicio se basa en sobrecargar a un objetivo con paquetes ICMP ( ping ). Al inundar un objetivo con más ping de los que es capaz de responder con eficacia, se puede producir una de denegación de servicio.
- Ping de la muerte: se le suele confundir con un ataque de inundacion de ping. El ping de la muerte implica el envío de un paquete malformado a una máquina objetivo que provoca un comportamiento dañino, como la caída del sistema.

==**Prevención**==

- Existen herramientas para tener un monitoreo continuo y poder analizar nuestro sitio web.
- Adquirir nuevos servidores y dispositivos de red para absorber más tráfico y peticiones.
- Soluciones hardware anti-DDoS.
- Recurrir a servicios en la nube.
___

## *Denegación de servicio distribuido (DDoS)*


Su principal objetivo es inhabilitar el uso de un determinado sistema o infraestructura para que no pueda prestar el servicio para el que está destinado. El ataque puede ir dirigido a la red informática o al servicio web.
En el ataque DDoS, los ciberatacantes generan numerosas peticiones desde diferentes equipos informáticos al mismo tiempo. A diferencia de lo que ocurre en el ataque DoS, cada petición proviene desde una determinada IP, de modo que se trata de un tipo de ataque mucho más complicado de detectar.

##### Tipos de ataques

- Volumétricos: la finalidad de un ataque DDoS volumétrico es sobrecargar una red con grandes cantidades de tráfico saturando el ancho de banda del recurso objetivo.
- Ataques de protocolos:  intentan consumir y agotar la capacidad informática de diversos recursos de infraestructuras de red,  como servidores o firewall, a través de solicitudes de conexión malintencionadas que vulneran las comunicaciones del protocolo.
- Capa de aplicación: los ataques a la capa de aplicación base miden en solicitud por segundo (RPS) y se realizan mediante la inundación de aplicaciones con solicitudes malintencionadas.

==**Prevención**==

- Actualizar el firmware del router.
- Usar una contraseña fuerte para el WiFi 
- Activar medidas de seguridad en la configuración del router.
- Mediate la contratación de servicios a compañías especializadas.

___

## *Economic Denial of Sustainability (EDoS)*


Nuevo tipo de ataque que afecta al servicio cloud y se aprovecha de las características de elasticidad y autoescalado de la nube para cargar en la factura de un usuario de la nube una cantidad excesiva de costes, ya que los atacantes se encargan de contratar servicios sin el consentimiento del usuario afectado