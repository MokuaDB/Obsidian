___

###### ¿Qué es el Blockchain?
Es un libro de contabilidad inmodificable y compartido en el que se registran todas las transacciones y realizar seguimiento de activos. Pueden ser tangibles o intangibles.
Se inició en 1991, cuando aparece la  `primera cadena de bloques segura` que utilizaba criptografía. Sin embargo, no se popularizó hasta la aparición de la primera criptomoneda estable en el mercado, **BITCOIN** .
Surgió en 2008 a manos de Satoshi Nakamoto, que hace referencia  a un pseudónimo. Esta criptomoneda se basó en la criptografía, tanto para administrar la propiedad como para asegurar el sistema.
Satoshi soluciono los problemas de  falta de confianza y autoridad central de las monedas virtuales anteriores, con un sistema Peer - to - Peer.
Estaba compuesto por ciertos principios:
- Un cifrado que garantizase tanto la propiedad como la identidad de los usuarios.
- Un mecanismo de consenso que validara las operaciones y protegiera la Red de operaciones duplicadas y fraudulentas.
- Y un libro de contabilidad que fuera seguro, es decir, inmodificable. Para ello hizo que fuese transparente y compartido y lo implementó con una cadena de bloques.

*Blockchain* es la tecnología que permite operar con criptomonedas. Se trata de una base de datos descentralizada, es decir, no existe solo en un único lugar ni la gestiona una única persona, sino que se encuentra replicada entre diferentes ordenadores o nodos y se rige por el concepto  P2P. Además está constantemente actualizada.

###### ¿Cómo funciona el blockchain?
- Cada operación es una transacción y un conjunto de transacciones componen un bloque.
- Solo cuando es verificado y validado por estos pasa a formar parte de la cadena de Blockchain.
- Cuando los bloques se suman a la cadena **no se pueden modificar ni eliminar**.
- Para que un bloque se una a la cadena todos los nodos mineros deben validarlo y para ello, se les plantea un algoritmo a esos nodos. El primero en resolverlo se lo comunica al resto y si esto es correcto, el bloque se acepta y pasa a formar parte de la cadena de bloques.


# Diccionario de términos

- Moneda virtual
	El dinero virtual es aquel que únicamente existe en formato digital. Estas monedas pueden ser cerradas o ficticias, es decir, no tienen ninguna conexión con la economía real.

- Criptomoneda
	Es un tipo de moneda virtual. Sin embargo, no existe un único emisor concreto de esta moneda, como sí lo hay en las monedas virtuales que sirven para la compra de productos dentro de la misma comunidad.
	Adicionalmente este tipo de monedas están protegidas por criptografía y tienen carácter descentralizado. Bitcoin, Ethereum y Dogcoin son las mas conocidas.

- Seudonimización
	Hace referencia al proceso que permite cambiar un conjunto de datos originales por un alias o seudónimo, es decir, no se sabe quién es cada usuario en la vida real.

- Wallet
	Se trata de un monedero virtual en el que se pueden gestionar los activos criptográficos, es decir, almacena y gestiona tanto claves públicas como privadas de las criptomonedas de las que disponga el usuario, donde la clave pública sería algo similar al número de una cuenta bancaria. Y la clave privada haría referencia al PIN o contraseña.

- Transacción
	Hace referencia a cada una las operaciones que se realizan en una red blockchain, y por tanto, agregan información a la cadena de bloques. 

- Minería de datos
	Se trata de la validación y agrupación en bloques de las transacciones que realizan los usuarios dentro de una red de blockchain para, posteriormente, unirlas a esta. Los mineros que realizan la minería se encargan de validar las transacciones y agruparlas en un bloque que pasará a formar parte de la cadena de bloques.

- Mempool
	Hace referencia al primer lugar donde se anota una transacción cuando un usuario la realiza, es decir, es una memoria temporal donde se almacenan las transacciones de los usuarios.
	El primer paso es la recepción de la transacción, es decir,  la mempool recibe las transacciones de los usuarios dentro de la Red; el segundo paso es el acceso por parte de los mineros a las transacciones que están en la mempool, donde seleccionan las transacciones que se van a incluir en el siguiente bloque de la cadena blockchain.

- Hash
	Es el resultado de una función hash, un algoritmo criptográfico que genera un identificador único e irrepetible a partir de una información. Tiene como objetivo formar una cadena de caracteres única y que garantice la no modificación de los datos a los que hace referencia (hash)

- Nonce
	Hace referencia a un número que solo puede usarse una vez, esto es, *number that can be only used once* . Se trata de un número arbitrario utilizado en criptografía para autenticar el bloque y , junto con el hash, evitar una posible manipulación de la información de los bloques.

- Árbol de Merkle
	Estructura de datos en forma de árbol que tiene el objetivo de facilitar la verificación de grandes cantidades de datos, relacionándolos a través de diferentes técnicas criptográficas y de manejo de información. Se trata de una *estructura de datos formada por varias capas, que relaciona cada nodo,* es decir, cada grupo de datos, *con una única raíz.*
	No debemos confundir aquí el concepto de nodo que se utiliza para referirse también a los ordenadores de una red blockchain. En los árboles de Merkle un nodo hace referencia a una transacción. Cada nodo debe contener un identificador único, un *hash*.
	