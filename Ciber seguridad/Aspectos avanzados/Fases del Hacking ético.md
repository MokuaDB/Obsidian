___

#### Fase 1: interacciones previas.

Hace referencia a las negociaciones o acuerdos entre el cliente y la organización, donde se definen los parámetros y el alcance del pentest. También decidirán la forma de ejecutarla, es decir, Black Box, White Box o Grey Box, siendo esta última la más común.

#### Fase 2: recogida de la información.

En esta fase se recopilará toda la información posible acerca del objetivo, para poder realizar el ataque de manera óptima, se trata de una fase de *footprinting*.
Existen dos modos de recopilar información:
1. Reconocimiento pasivo o footprinting
	El hacker recoge la información necesaria sobre su objetivo, sin la necesidad de interactuar con él.

2. Reconocimiento activo o fingerprinting
	Recopila la información mediante la interacción con el objetivo. Este tipo de reconocimiento puede aportar mayor información sobre la víctima.


#### Fase 3: modelado de amenazas.

Se organiza y analiza toda la información recopilada desde un punto de vista externo, como los activos, recogiendo información, servidores,base de datos, versiones, ubicación, procesos de negocios.
Esta fase a parte de producir un modelo de amenazas, también elabora una lista de mejoras de seguridad que deberían implementar.


#### Fase 4: análisis de vulnerabilidades.

Escanear los sistemas y la Red para descubrir las brechas de seguridad que existen. Este proceso se lleva a cabo a través de herramientas específicas, tanto automáticas como manuales.

- Herramientas
	1. OWASP (Open Web Application Security Project) organización sin ánimo de lucro que promueve el desarrollo seguro de software y orientada al análisis web.
	2. OWASP ZAP herramienta gratuita que permite probar aplicaciones web y se presenta domo [[Proxy]] intermediario.
	3. Kali Linux es una distribución de linux enfocada a realizar auditorías, pentesting y pruebas de hacking ético.
	4. Nmap (Network Mapper) herramienta gratuita y de código abierto utilizada para descubrir redes y realizar auditorías.
	5. Nessus herramienta gratuita muy popular que permite el escaneo de vulnerabilidades de seguridad en diferentes SO.
	6. OpenVAS (Open Vulnerability Assessment System Scanner) herramienta de software libre y gratuita que escanea y gestiona brechas de seguridad.

#### Fase 5: explotación.

En esta fase se realiza una prueba de penetración técnica centrada, exclusivamente, en el aprovechamiento de las vulnerabilidades detectadas.

- ¿Qué es un *exploit*?
	Programa informático, que aprovecha una vulnerabilidad o fallo para provocar un comportamiento no intencionado.

- Metasploit
	Esta herramienta es un framework, entorno de trabajo, que facilita la investigación y análisis de vulnerabilidades de seguridad para poder mitigar los riesgos existentes.

#### Fase 6: publicación de explotación.

Se centra en la recolección de información privilegiada o confidencial que esté alojada en el servidor o en el sistema, con el objetivo de demostrar al cliente lo que podría ocurrir en caso de que se accediera a los sistemas.

#### Fase 7: informe.

Redacción detallada de las acciones realizadas, junto con todos los errores de seguridad y vulnerabilidades que se han detectado en los procesos.

- Informe técnico
	Dirigido a los administradores del sistema. Este informe detalla la terminología y tecnicismos apropiados, además, anexa las posibles soluciones que se deberían implementar.

- Informe ejecutivo
	Informe dirigido a los directores de la organización, por lo que debe redactarse de tal manera que sea comprensible para aquellas personas ajenas a los tecnicismos informáticos.
