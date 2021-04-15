# Bitacora de comandos LINUX
- **lsb_release** => comando para ver la distribución que está instalada y su versión.
  - **lsb_release-a** =>  La "a" del comando muestra toda la información.
- **sudo** => usado para acceder archivos restringidos y operaciones.
  - **sudo su** => para correr comandos con permisos de administrador.
   - **sudo apt install nombrePrograma** => para instalar alguna aplicación o programa.
   - **sudo apt search nombreApp** => busca la aplicación digitada y su información.
   - **sudo apt update** => lee la lista de carpetas disponibles.
   - **sudo apt upgrade -y** => para decir yes a todo.
   - **sudo apt upgrade** => instala los nuevos paquetes.
   - **sudo cp nombreArchivo1 nombreArchivo2** => hace una copia del primer archivo.
   - **sudo mkedir** => crea el sistema de archivos.
   - **sudo mount** => monta el sistema de archivos.
   - **sudo mount -
   - **sudo chmod 700 nombreArchivo** => cambia los permisos del archivo, en este caso es 700.
   - **sudo dmidecode --type17** => información sobre memoria. 
   - **sudo mkdir /mnt/ram_disk** => para montar una unidad RAM DISK.
   - **sudo mount -t tmpfs -o size= 1024m new_ram_disk/mnt/ram_disk** => para montar una unidad RAM DISK.
   - **sudo fdisk -l** => para listar todas las particiones existentes en nuestro sistema.
- **ls** => muestra las carpetas/archivos actuales (los directorios).
   - **ls rutaCarpeta** => muestra los archivos dentro de la carpeta digitada.
   - **ls-la** => muestra los archivos de forma de lista detalla (lista los archivos). La "a" del comando es para mostrar los archivos ocultos.
   - **ls -l nombreArchivo** => muestra la información del archivo
- **clear** => limpia la pantalla de la consola.
- **pwd** => muestra la ruta actual.
- **mkdir nombreCarpeta** => crea una carpeta nueva con el nombre digitado.
- **cd nombreCarpeta** => cambia el directorio a la carpeta que uno digito.
  - **cd..** => para volver a la carpeta de antes (home).
- **touch** => crea un archivo vacío. Ej: touch archivo.txt
- **nano nombreArchivo** => edita el archivo digitado.
- **cat nombreArchivo** => imprime en la consola el contenido del archivo digitado.
   - **cat /proc/meminfo** => para ver la información sobre la memoria. 
- **uname-a** => muestra la versión del kernel de Linux.
- **top** => muestra los procesos que están corriendo en el sistema operativo.
  - **htop** => hace lo mismo que top pero más bonito.
- **ps** => muestra los procesos activos.
  - **ps-aux** => muestra todos los procesos que hay en el sistema operativo.
- **kill** => es un comando que envía una señal de terminación.
  - **kill-9 idProceso** => mata/cierra el proceso o app con el id de este (pid).
- **pstree** => se ven los procesos pero en tipo árbol (se puede ver como los procesos que tienen hijos).
- **history** => para ver el historial de comandos que se ha digitado.
- **free -h** , **swapon** , **cat /proc/sys/vm/swappiness** => muestra cuanto es el swap que se está utilizando
- **stat nombreArchivo** => muestra la fecha de creacion y su último acceso.
- **file nombreArchivo** => muestra el tipo de archivo (carpeta, acceso directo).
- **chown user1 nombreArchivo** => muestra el propietario, grupo, lista de permisos chown.
- **df -h** => comando para poder ver todos los sistemas de archivos corriendo en el equipo.
- **stat nombreArchivo** => fecha de creación y último acceso del archivo puesto.
- **file nombreArchivo** => muestra el tipo de archivo (si es carpeta, acceso directo).
- **mount** => montaje de dispositivos en el sistema de archivos.
- **du nombreArchivo** => muestra el tamaño del archivo.
  - **du -h nombreArchivo** => muestra el tamaño del archivo especificando si es GB, MB, etc. 
  - 
- **chown user1 nombreArchivo** o **chmod 777 nombreArchivo** => muestra el propietario, grupo, y lista de permisos chown.
**chmod 755** => agrega el permiso de ejecucion.
**sudo chmod 700 nombreArchivo** => cambia los permisos del archivo, en este caso 700. 
**Gparted** => administra las particiones (aplicación).
**gnome-disk-utility** => muestra informacion sobre el disco (aplicacion).
**Testdisk** => para recuperar archivos eliminados.
**bash --version** => para ver la version de shell. 
**echo $SHELL** => muestra cual es el shell que se esta utilizando.
**cat /etc/shells** => para ver los shells que existen.
**zsh** => para cambiarse al shell.
**./script.sh** o **bash script.sh** => para ejecutar el archivo en bash y el primero para powershell.
**zenity -h** => para ver las opciones de zenity.


