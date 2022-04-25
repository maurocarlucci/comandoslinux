# comandoslinux
Este es un repositorio de comandos de Linux del curso de Sistemas Operativos
| Comando | Descripcion | Ejemplo |
| :---         |     :---:      |          ---: |
| ls   |  enseña los archivos del pc    | para poder ver los archivos de la maquina    |
| cd   | Contenido de la celda       | cd para entrar al directorio indicado      |
| man   | Manual del sistema       | se usa para poder revidar el maual del sistema en caso de algun problema      |
| sudo su   | Convertirse temporalmente en super usuario       | sudo su para poder ingresar a algun programa como super usuario      |
| whoami   | para saber quien es el usuario       | En caso de no saber con que usuario se ingreso al sistema      |
| cp   | sirve para copiar un archivo y elegir donde quiero que se guarde el nuevo archivo       |  cp texto.txt /home/usuario/carpeta_de_destino/     |
|wget|Descargar desde internet|wget -q https://packages.microsoft.com/keys/microsoft.asc%7C
|pacman|Package manager de arch| sudo pacman -Syuu|
|useradd|Crea un nuevo usuario| sudo useradd -m newUser -G wheel -p 123456|
|touch|Crea un nuevo archivo txt| touch file.txt|
|mkdir|Crea un nuevo directorio| mkdir arroz|
|rmdir|borra un directorio| rmdir -rf arroz|
|tree|hace una lista en forma de arbol de los directorios que hay| tree|
|ls|Lista un archivo en una ruta| ls -l /bin/|
|cat|Imprime el contenido de un archivo| cat file.txt|
|mv|Mueve un archivo a una ruta especifica| mv file.txt /bin/|
|grep|Para buscar en archivos| grep -rin "log" /home/*|
|ps|Imprime los procesos| ps -A|
|chmod|Cambia los permisos para los archivos| chmod 777 file.txt|
|su|Para cambiar de usuario| su - newUser|
|pkill|Termina el proceso| sudo pkill colord|
|history|Enseña todos los comandos utilizados| history|
|ln|Crea un link con el archivo| ln -s /var/log/pacman.log ~/pacman.log|
|crontab|Configurar crontab Daemon| crontab -e|
|nano|editor de texto| nano file.txt|
|vim|editor de texto| vim file.txt| 
|images|enumera todas las imagenes con detalles| docker images|
|run|ejecuta la imagen|docker run -it -d httpd |
|ps|enumera todos los contenedores|docker ps |
|ps -a|todos los contenedores que se ejecutan /salieron/ detuvieron| docker ps -a |
|axec|accede al contenedor y ejecuta comandos dentro del contenedor| docker axec -it 09ca6feb6efc bash|
|rm|eliminar contenedor|docker rm 9b6343d3b5a0 |
|rmi|eliminar imagen|docker rmi fce289e99eb9 |
|restart|reiniciar docker|docker restart 09ca6feb6efc |
|kill|detener el contenedor|docker kill 09ca6feb6efc |
|search|Busca una imagen de docker|docker search hadoop |
 
