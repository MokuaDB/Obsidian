___

La **Criptografía** hace referencia al procedimiento que se encarga de traducir un texto sin formato, es decir, un texto plano o *plain text*, en una secuencia inteligible de caracteres empleando,para ello, unas reglas específicas. denominadas algoritmos y una clave, con el objetivo de que el texto cifrado resultante sea legible exclusivamente para aquellos que disponen de la clave para descifrarlo y conocen el algoritmo.

###### Conceptos clave
- Codificar: hace referencia a la técnica en la que los datos se transforman de un formato a otro ara que puedan ser entendidos y utilizados por diversos sistemas. Se utiliza el mismo algoritmo, tanto para codificar como para descodificar. Algunos ejemplos son el código morse o ASCII.

- Cifrado: el cifrado convierte los datos en ilegibles y difíciles de decodificar para alguien que no disponga de la clave, un factor esencial en el cifrado. Con la clave se cifran los datos y se descifran, aunque como veremos es posible que la clave de cifrado no sea la misma.


###### Ejemplos de cifrado

- **Cifrado César**
	- Unos de los primeros métodos de cifrado. Tiene su origen en la época de Julio César. También denominado cifrado por desplazamiento, para proteger su correspondencia militar. Se basa en la sustitución alfabética simple por la que cada letra del alfabeto se desplaza un número de posiciones determinado por la clave.
	- Si la clave es 13, significa que desplazamos 13 posiciones las letras del alfabeto (ROT13).

La codificación moderna se basa en algoritmos, que combinan la *sustitución y transposición* :
- La sustitución hace referencia al cambio de cada carácter por otro.
- La transposición hace referencia al cambio de un texto plano siguiendo un esquema definido, donde las unidades de texto pueden ser una sola letra, pares o tríos

El algoritmo criptográfico se encarga de describir el método encriptado. Con el método César el algoritmo sería "desplazar cada letra en el abecedario de acuerdo a la clave"
Y la clave es el valor o variable que se utiliza para realizar el cifrado. En el ejemplo anterior la clave sería ROT13.

###### Objetivos de la criptografía.

- **Confidencialidad**: la información solo puede ser legible por aquellas personas a las que está dirigido el mensaje.
- **Integridad**: garantiza la inmutabilidad de la información en el proceso de almacenamiento o tránsito.
- **No repudio**: el emisor de la información no puede negar su autoría, es decir, permite vincular la información o el mensaje a una persona.
- **Autenticación**: tanto el emisor como el receptor pueden confirmar la identidad del otro.

###### Tipos o métodos criptográficos.

* **Criptografía simétrica** : este método se basa en que, tanto el cifrado como el descifrado emplean la misma clave secreta.
* **Criptografía asimétrica**: cada interlocutor cuenta con dos claves de manera individual, una pública y una privada. Para comunicarse entre sí cada uno debe conocer la clave pública del otro, mientras que la clave privada debe ser secreta para asegurar la confidencialidad. La clave pública se utiliza para cifrar la información y la clave privada para descifrarla.
* **Criptografía híbrida**: este tipo de criptografía consiste en el uso de algoritmos, tanto simétricos como asimétricos. El objetivo es aprovechar las ventajas de ambos métodos y disminuir el tiempo y consumo de recursos de la criptografía asimétrica.
- *Método PGP*
	 Del inglés Pretty Good Privaacity, es un programa de cifrado híbrido creado por Phil Zimmermann, que permite cifrar cualquier tipo de información personal, haciendo uso de la criptografía asimétrica público/privada. 
	 Existen distintas herramientas gratuitas como Gpg4win(Kleopatra), PGPTool y Portable PGP.


###### Función criptográfica HASH.

Debemos comprender el concepto de hash, ya que es muy utilizado en criptografía, pero también en otros ámbitos como el blockchain y en la firma de archivos y evidencias digitales para confirmar que no han sido modificados.
Una función critográfica hash es un algoritmo matemático que se encarga de transformar un bloque de datos de entrada en una nueva serie de caracteres, que normalmente tiene un longitud fija.

 **Tipos de algoritmos**
- MD5(1991): comprometidos desde 2004.
- SHA-1(1995): compremetidos desde 2005.
- SHA-2: en función de su rango de salida puede ser un algoritmo SHA-224, SHA-256.

###### Uso hash:
- Contraseñas
	Los valores hash se utilizan habitualmente en la protección de contraseñas para no guardarlas en texto claro en una base de datos. Cuando un usuario se registra en una página web, no es la contraseña la que se almacena en la base de datos sino que se guarda su valor hash.

- Integridad contenidos
	Otras de las funciones hash es asegurar la integridad de los mensajes.
	>¿Cómo funcionaría esto? Si se aplica la función hash a un mensaje al enviarlo y se vuelve a aplicar la función hash al recibirlo, siendo el valor del hash el mismo, esto significará que la comunicación ha sido segura y los datos no han sido alterados. En cambio si los hashes son diferentes significa que el mensaje ha sido alterado.

	Este mecanismo se utiliza también para descargar ficheros de una página web.

- Características de hash
	- Unidireccionalidad: una vez que se ha calculado el hash de un texto o fichero, no es posible hacer el cálculo inverso.
	- Comprensión: no importa el tamaño del texto o fichero original, ya que el valor resultante de aplicar el hash siempre tendrá la misma longitud.
	- Facilidad de cálculo y bajo costo: la necesidad de sencillez a la hora de aplicar la función hash a cualquier texto o fichero independientemente de su tamaño, de forma que este cálculo sea rápido y no se pierda tiempo.
	- Difusión de bits: el valor hash debe ser una función compleja que haga una mínima variación en el texto o fichero original produzca un hash completamente diferente.
	- Determinista: al aplicar la función hash sobre el mismo texto o fichero, siempre se obtendrá el mismo resultado.
	- Resistencia a fuertes colisiones: es difícil encontrar un par de textos con el mismo valor hash.