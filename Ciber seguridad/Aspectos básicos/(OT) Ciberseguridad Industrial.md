___
La ciberseguridad es un campo que no afecta solo a los sistemas informáticos de una oficina, sino que también afecta al entorno industrial. A medida que fueron incorporando la automatización y la tecnología, ha ido evolucionando hasta lo que se conoce como Industria 4.0.

- Industria 1.0 -> Mecanización, vapor y telar.
- Industria 2.0 -> Producción en masa, línea de ensamblaje, energía eléctrica.
- Industria 3.0 -> Automatización, ordenadores y electrónica.
- Industria 4.0 -> Sistemas físicos cibernéticos, IoT, redes.

La ciberseguridad industrial aúna diferentes principios de seguridad de los entornos OT y principios IT, con el fin de proteger los distintos activos de una industria.ciberseguridad

## Pirámide de automatización industrial

Representa la integración de la tecnología en la industria. Existen cinco niveles:

>Nivel 0 (Red de campo) --> Instrumentación (sensores,actuadores,etc)
>Nivel 1 (Red de control) Plc, DCS
>Nivel 2 (Red de supervisión) SCADA, HMI
>Nivel 3 (Red de planificación) MES
>Nviel 4 (Red de gestión) ERP

Del nivel 0 - 3 pertenece a OT y los niveles 3 - 4 IT

- Nivel 0: red campo
	Hace referencia a todos aquellos dispositivos que se utilizan para la instrumentación, es decir, para realizar trabajo físico y la monitorización. 
	
	- Sensores: estos mecanismos generan señales eléctricas a partir de variables físicas como la temperatura, el nivel o la velocidad.
	- Actuadores: estos sistemas convierten la energía en movimiento o sirven para activar el funcionamiento de otro dispositivo acoplado a él. Por ejemplo, las válvulas o bombas mantienen variables, como el flujo, el calor o la presión dentro de unos parámetros establecidos.
	- Mecanismos: estos dispositivos se activan a raíz del funcionamiento de los actuadores a los que están conectados.

-  Nivel 1: red de control
	Permite a los operadores controlar las variables, acutando como el "cerebro".
	- El controlador lógico programable o PLC (Programmmable Logic Controller) se encarga de procesar los datos del nivel 0 y emitir órdenes a otros dispositivos, tanto de nivel 1 como 0.
	- El sistema de control distribuido o DCS (Distributed Control System), realiza la misma función que el PLC, con la diferencia que, en este caso, encontramos varios dispositivos de control distribuidos de forma geográfica, que se gestionan desde un punto de control específico.

- Nivel 2: red de supervisión
	- SCADA ( Supervisory Control and Data Acquisition): sistema que controla múltiples máquinas en diferentes procesos complejos. Se encara de controlar , supervisar, recopilar y analizar datos y generar informes, lo que permite mejorar la eficiencia de los procesos, tomar mejores decisiones de negocio y comunicar los problemas que puedan surgir. Además permite almacenar esos datos en base de datos para su posterio análisis.
	- HMI (Human Machine Interface): esta interfaz permite que un usuario u operario pueda interactuar con un dispositivo. Normalmente se utiliza para la monitorización o visualización de lo que ejecuta el SCADA, aunque también lo podemos encontrar en el nivel  con los PLC.

- Nivel 3: red de planificación
	En el nivel de planificación o red de operación, encontramos los sistemas MES (Manufacturing Execution System) que ofrecen datos e información, permitiendo así la optimización de las actividades de producción. Los sistemas MES guían, inician, responden e informan sobre las actividades que estás sucediendo en la planta a tiempo real.
	El sistema MES engloba los datos de todos los procesos de fabricación que suceden en la planta, es decir, está relacionado con los sistemas SCADA y los HMI.
	Sistemas MOM (Manufacturing Operations Management), hace referencia a un concepto mas global, aportando una visibilidad completa de los procesos de fabricación.

- Nivel 4: red de gestión
	Sistemas que administras los recursos empresariales (ERP). Estos ERP proporcionan información global de la producción de una organización. Mientras que los sistemas MON MES monitorizan y controlan los procesos de fabricación. los ERP permiten seguir y controlar toda la organización.

## Ataques a entornos OT

>2010 Ataque a Stuxnet, instalación nuclear iraní. Se destruyeron 1000 máquinas en la centrar nuclear de Natanz, Irán.
>2014 Ataque fábrica de acero alemana. Afectó a numerosos sistemas, imposibilitando el apagado controlado del alto horno y causando un daño masivo a la infraestructura de la fábrica.
>2017 Ransomware WannaCry.
>2021 Darkside a oleoducto Colonial Pipeline. Un ransomware que afectó al suministro de combustible en EE.UU. y produjo una brecha de seguridad.

*El grupo [Darkside](https://www.kaspersky.es/blog/pipeline-ransomware-mitigation/25302/) pudo acceder a los sistemas a través de una contraseña compremetida de un empleado*
