El sistema operativo Linux está estructurado en una jerarquía en forma de árbol. Linux está estructurado con los siguientes directorios estándar de nivel superior:

`/`  The top-level directory is the root filesystem and contains all of the files required to boot the operating system before other filesystems are mounted as well as the files required to boot the other filesystems. After boot, all of the other filesystems are mounted at standard mount points as subdirectories of the root.

`/bin`  Contiene los binarios de los comandos esenciales.

`/boot` Consiste en el gestor de arranque estático, el ejecutable del núcleo y los archivos necesarios para arrancar el sistema operativo Linux.

`/dev` Consiste en el gestor de arranque estático, el ejecutable del núcleo y los archivos necesarios para arrancar el sistema operativo Linux.

`/etc` Archivos de configuración del sistema local. Los archivos de configuración de las aplicaciones instaladas también pueden guardarse aquí.

`/home` Cada usuario del sistema tiene un subdirectorio aquí para su almacenamiento.

`/lib` Archivos de bibliotecas compartidas necesarios para el arranque del sistema.

`/media` quí se montan los dispositivos externos extraíbles, como las unidades USB.

`/mnt` Punto de montaje temporal para sistemas de archivos normales.

`/opt` Aquí se pueden guardar archivos opcionales, como herramientas de terceros.

`/root` El directorio personal del usuario root.

`/sbin` Este directorio contiene ejecutables utilizados para la administración del sistema (archivos binarios del sistema).

`/tmp` El sistema operativo y muchos programas utilizan este directorio para almacenar archivos temporales. Este directorio suele borrarse al arrancar el sistema y puede eliminarse en otros momentos sin previo aviso.

`/usr` Contiene ejecutables, librerias, archivos de manual, etc.

`/var` Este directorio contiene archivos de datos variables, como archivos de registro, bandejas de entrada de correo electrónico, archivos relacionados con aplicaciones web, archivos cron, etc.
