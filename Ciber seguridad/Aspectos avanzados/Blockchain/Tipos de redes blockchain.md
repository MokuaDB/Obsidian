___
- Red pública
	- Es una red abierta y por lo tanto cualquier usuario puede unirse y participar. 
	- La gran ventaja es que no existe coste de infraestructura
	- El único requisito es una gran potencia de computación para la resolución de algoritmos por parte de los mineros.

- Red privada
	- Es necesaria una invitación que debe ser validada, ya sea por el creador o por una serie de reglas establecidas previamente.
	- La ventaja más destacable de este tipo de red es su alto nivel de privacidad.
	- Las empresas que utilizan este tipo de red son MONAX, Blockstack o Multichain.

- Red federada o de consorcio
	- Formadas por un grupo, ya sea compañías o personas individuales. Por lo que comparten responsabilidad a la hora de mantener la red.
	- Ofrecen mayor control y privacidad, además son más escalables y rápidas. B3i, EWF o R3.

###### Tipos de bloques.

- Bloque génesis
	Se trata del primer bloque de la cadena y permite que se puedan realizar las sucesivas transacciones, ya que a raíz de este primer bloque se puede comenzar a crear el historial de operaciones, es decir, posibilita la creación de nuevos bloques y la asociación del nuevo bloque con el anterior

- Bloque válido
	Es aquel bloque que ha sido minado. Los nodos o usuarios han resuelto el primer problema matemático que se le planteó. Con esa solución, y su posterior comunicación al resto de nodos, se valida el bloque y pasa a formar parte de la cadena.

- Bloque suelto o huérfano
	Es un tipo de bloque válido, pero que no forma parte de la cadena. Antiguamente, en las primeras versiones del software Bitcoin, esto ocurría cuando no se conocía la ascendencia completa del bloque (no se conocía el bloque padre).

- Bloque no válido
	Es aquel bloque que han intentado modificar, por ejemplo, cambiando su hash.

###### Cadena de bloques.

Para entender la formación de la cadena de bloques nos basaremos en esta imagen. Se parte de un bloque original y vamos por los bloques grises formando la cadena. Los bloques que no pertenecen a la cadena principal son los llamados bloques huérfanos.

###### Esquema de bloques.

Cada bloque está formado por distintos datos :
- Hash del bloque previo
	Este identificador único permite que un bloque pueda vincularse con el anterior y así poder formar parte de la cadena.

- Timestamp
	Marca de tiempo. Permite la identificación del momento en el que el bloque fue creado.

- Nonce
	"Number that can be only used once". Número arbitrario empleado en criptografía que garantiza que los hashes antiguos no se puedan volver a utilizar.

- Hash árbol Merkle
	Permite referenciar toda la información del bloque a través de ese nodo raíz.

- Información de transacción
	Contiene la información de las transacciones.


###### SmartContracs o contratos inteligentes

Se trata de acuerdos digitales automatizados en los que se elimina al intermediario, es este caso, un fedatario o tercero, que vele por el cumplimiento del contrato. Se trata de *scripts* que se ejecutan de forma automática.

###### Ámbitos de aplicación

- Finanzas
	Su aplicación por excelencia son las criptomonedas. Esta tecnología permite registrar de forma inalterable y segura las diferentes operaciones realizadas entre individuos. 

- Ciberseguridad
	Permite almacenar la información y los datos de forma descentralizada y  cifrada. Aumenta enormemente la seguridad si su empresa se encuentra en diferentes lugares, ya que si se produce un ataque no podrían llegar a robar datos ni tampoco modificarlos.

- Distribución de arte (NFT)
	Permite que los artistas vendan sus obras a través de blockchain, e incluso que el autor se lleve un royalty, es decir, una compensación económica.

- Educación
	Permite la emisión d títulos acreditativos, certificados y todos aquellos documentos oficiales de forma veraz. asegurando así su autenticidad.

- Organización sin ánimo de lucro.
	Garantizan que las donaciones se transmitan de forma adecuada, y además permiten realizar operaciones en lugares donde se carece de infraestructura bancaria.