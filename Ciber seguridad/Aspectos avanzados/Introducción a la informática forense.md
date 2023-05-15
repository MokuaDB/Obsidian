___

El término forense hace referencia al arte de debatir. Su raíz *foro* hace referencia al lugar público de la antigua Roma donde estaba el Senado u discutían asuntos legales.
Este término evolucionó y pasó a hacer referencia al proceso científico que se establece para recopilar, analizar y presentar las evidencias recogidas.
Por lo tanto, la informática forense __es el proceso de investigación de los sistemas informáticos__ para detectar todas aquellas evidencias que puedan ofrecer información sobre los hechos.

>Informe técnico realizado por un experto en la materia, es decir, el perito informático, para valorar las posibles circunstancias relevantes relacionadas con un proceso judicial.

###### Estándares y protocolos

- UNE 197010:2015
- UNE 71506:2013
- ISO/IEC 27037:2012
- ISO/IEC 27042:2015 


###### Objetivos

- Compensar los daños causados por intrusos o criminales.
- Perseguir y procesar judicialmente a los criminales.
- Crear y aplicar medidas para la prevención de casos similares.

###### Tipos de análisis forense

- *Dispositivos*
	Se hace una copia de los procesos que se están ejecutando en el dispositivo (volcado de la memoria RAM), así como los componentes de almacenamiento que el dispositivo tenga.Todo ello sin alterar el estado del dispositivo.
	Se realiza:
	1. ___En el equipo donde se ejecutó la acción a investigar.___
	2. ___En el equipo de la víctima.___
	3. ___En un equipo intermediario___, desde un ordenador que funcione como proxy o esté infectado por una botnet.

- *Red*
	Tiene como objetivo recopilar, monitorizar, y analizar las actividades de la red para descubrir intrusiones o malware. Se realiza a través de dos métodos:
	1. ___Atrápalo como puedas:___ recopila y monitoriza todo el tráfico de la Red.
	2. ___Para, mira y escucha:___ monitoriza los paquetes, pero solo captura y analiza los que sean sospechosos.

- *La nube*
	Se realiza cuando no se dispone de dispositivo físico o no se tiene aacceso al mismo, como en el caso de los servidores alojados en un *data center* pero una vez que se accede a ellos el procedimiento es el mismo que cuando analizamos un red.

###### Principales fases para realizar un análisis forense.

- *Preservación*
	- Consiste en recolectar las evidencias en base a los criterios de autenticidad, confiabilidad e integridad.
	- Un aspecto clave de esta fase es garantizar que estas pruebas no se alteren o destruyan.

- *Documentación*
	- Consiste en documentar todas las actividades llevadas a cabo, qué herramientas se utilizaron y en qué versión, qué pasos se realizaron, y siempre se debe seguir un orden temporal.

- *Adquisición*
	- En esta fase se harán copias del disco duro, la memoria, el historial de llamadas, los correos electrónicos, etc... y sobre ella se realizarán las pruebas necesarias de la fase posterior de análisis.

- *Análisis*
	- Se realizaran los procesos y tareas necesarias sobre las evidencias adquiridas.
	- ¿Cuál es el objeto de esta fase? El objetivo es encontrar la evidencia digital que permita detectar el hecho, saber quién lo hizo o relacionar el hecho con un sujeto, de cara al proceso judicial.

- *Presentación*
	- Se redacta el informe pericial, que recoge toda la información recopilada.


###### Evidencias digitales

Hace referencia a cualquier registro de datos o información que se almacena o se transmite a través de un sistema informático, es decir, cualquier dato digital que pueda usarse en un juicio. Deben cumplir tres criterios:
1. ___Autenticidad:___ la prueba debe haber sido obtenida y registrada en el lugar de los hechos, y no puede estar alterada.
2. ___Confiabilidad:___ la prueba debe provenir de fuentes fiables.
3. ___Integridad:___ para que la prueba sea suficiente debe estar completa.

###### Tipos de evidencias digitales

- ___Según el tipo de elemento___
	- *Evidencia hardware*: herramienta o dispositivo físico que sirve para probar o que se ha utilizado en el delito o el crimen.
	- *Evidencia digital*: todos los datos, programas o información que hayan sido utilizados para realizar un acto que esta prohibido.

- ___Según el tipo de sistema___
	- *Sistema de computaciión abiertos*: ordenadores, servidores y periféricos.
	- *Sistemas de telecomunicaciones*: redes cableadas e inalámbricas y todo el conjunto descentralizado de redes.
	- *Sistemas de computación convergentes*: sistemas o dispositivos que poseen convergencia digial. Móviles, tarjetas inteligentes (NFC).

- ___Según la fuente___
	- *Generada por ordenador*: aquella que se crea por el sistema de seguridad en el momento en que se produce un evento y se genera un registro o log.
	- *Generada por una persona con el ordenador*:  queda almacenada en el equipo, pudiendo demostrarse así la identidad de quien la generó.
	- *Combinación de las anteriores*: se dispone de los logs y las evidencias del usuario.

###### Características de las herramientas de informática forense

- ___Recuperar archivo___ eliminados o borrados.
- ___Recuperar información___ de datos de sesión.
- ___Ver historiales___ de navegación, conversaciones, correos...
- ___Analizar la infraestructura___ de las comunicaciones, como pueden ser los protocolos o las configuraciones realizadas en los dispositivos.
- ___Analizar las imágenes y documentos___ para descubrir su autenticidad.
- __Detectar vulnerabilidades__ a través de un análisis de seguridad.
- __Rastrear el origen__ de posibles filtraciones de información que supongan una vulneración de los derechos fundamentales de privacidad y protección de datos.