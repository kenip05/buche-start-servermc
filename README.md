# bucle-start-servermc
El archivo se debe poner en la misma carpeta que el ".jar", dentro del archivo podremos modificar los MB que usaremos para el servidor.

Su funcionamiento es muy simple, el "start.sh" lo usaremos cuando nuestro sistema sea Linux y posea la shell "/bin/bash" importante recalcar que se le debe dar permisos de ejecición a este archivo, lo haremos con el siguiente comando dentro de la carpeta donde se encuentre: "chmod u=rwx start.sh". Una vez hecho, editaremos el archivo con "nano" y pondremos el nombre del .jar a ejecutar, guardamos y ejecutamos el archivo escribiendo "./start.sh".

En el caso que nuestro sistema sea Windows, solo necesitaremos editar el archivo y poner el nombre exacto del .jar, guardar y ejecutarlo.
