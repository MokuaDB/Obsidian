### Configuración Obsidian móvil para poder subir archivos a GitHub.
1. Instalar obsidian y termux en tu móvil.
2. Tendrás que actualizar termux con `apt update` . Después instalar git y ssh `apt install git openssh`
3. Configurar el almacenamiento de Git. Configure el almacenamiento para termux usando el comando: `termux-setup-storage`. Te pedirá que accedas al almacenamiento de tu teléfono móvil. Permita que esto continúe.
4. Conectarse a GitHub a la vez que creas las llaves ssh. Con el comando `ssh-keygen -t rsa -C "Email_github"` . En el email tendrás que poner el correo asociado que tengas en GitHub. 
5. Para finalizar inicia sesión en GitHub usando el comando `ssh -T git@github.com` . Esta es la manera más fácil de conectarse a GitHub desde el móvil.
6. En el directorio de almacenamiento compartido que has creado en Termux (paso 3 /storage/shared/) clona tu repositorio: OJO si ya estabas usando Obsidian en el móvil y quieres subirlo todo a GitHub, recomiendo clonar primero tu repositorio `git clone git@github.com:[nombre de tu usuario en GitHub]/mirepo.git`
7. 

