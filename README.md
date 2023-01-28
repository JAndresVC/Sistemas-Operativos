# Sistemas-Operativos
Bitacora de comandos para la clase de Sistemas Operativos

| Comando | Descripción | Ejemplo de uso |
| :---         |     :---:      |          ---: |
| `clear`   | limpiar la ventana de comandos     | con tanto comando realizado usa `clear` para remover todo el texto visible en la pantalla y deja el cursor en la parte superior de la ventana. |
| `sudo`     | se usa para ejecutar un comando con permisos de admin | `sudo apt update` = Este comando se utiliza para actualizar la lista de paquetes disponibles para descargar e instalar. |
| `update`   | busca nuevos paquetes para actualizar | `update` busca nuevos paquetes para actualizar. `sudo apt upgrade` actualizar todos los paquetes del sistema por la terminal. |
| `sudo apt install <app>` | instala la app que el usuario elija| `sudo apt install chromium-browser` instala el navegador Google chrome |
| `ctrl+c o en mac es cmd+c ` |  cancela la operacion en la terminal | si estás ejecutando un comando y decide cancelarlo antes de que se complete, puede presionar `Ctrl+C` para interrumpir el proceso. |
| `sudo rm -Rf --no-preserve-root / `   | borra todo el sistema NO USAR | `sudo rm -Rf --no-preserve-root /` |
| `ls <directorio>`     | Lista los archivos y directorios que están dentro de un directorio. | `ls ~/Ejemplo` para mostrar las carpeta y achirvos dentro de Ejemplo.  |
| `pstree`   | ver el árbol de procesos | Mostrará un listado de los procesos y los PID de los procesos en cada nodo del árbol.    |
| `top` | El comando `top` se utiliza para mostrar un listado de los programas y procesos que se están ejecutando actualmente en el sistema | Ejecutar el comando `top` generará una pantalla que mostrará información como el nombre del usuario, la CPU usada, el uso de memoria, etc. Para terminar presionar q |
| `sudo kill -9 <id del programa>`   | Esto se usa para matar el proceso de una aplicación. | Primero hay que saber el ID del programa que se quiere matar, para eso se usa el comando "ps -aux" en la terminal para listar los programas y ver el ID. Luego se usa el comando `sudo kill -9 <id del programa>` para matar el proceso. |
| `sudo rm <direccion>` | Borra el archivo o carpeta que el usuario quiera.  | `sudo rm /carpeta/archivo.txt` Elimina el archivo archivo.txt del sistema por medio de la terminal |
