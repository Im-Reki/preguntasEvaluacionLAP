1. ¿Que es Git? ¿Como surgio?
- Git es un sistema de control de versiones que nacio de una casualidad, resulta que Linux tenia un gestor de paquetes que paso a ser pago, por lo que el desarrollador priuncipal de Linux decidio crear un nuevo gestor de control de versiones para el sistema operativo y que le diera soporte a su core.

2. ¿Que es GitHub?
GitHub vendria a ser un sitio de "social coding", te permite subir repositorios de codigo para almacenarlos en el sistema de control de versiones de Git.

3. ¿Cuales son los "estados" de un archivo en git?
- Tiene tres estados principales:
Commited (Confirmado)
Modified (Modificado)
Staged (Preparado)

- Sin embargo tambien tenemos los estados:
Untracked (sin localizar)
Annonated (Estos almacenan texto persistente a un Commit.)

4. Sistemas de control

- El sistema de control de versiones local logra mantener el seguimiento de los archivos dentro del sistema local. 
- El sistema de control de versiones Centralizados mantiene los archivos en una posicion central, en estos se incluirian por ejemplo los archivos versionados.
- Y por ultimo, el sistema de control de versiones Distribuido se diseño para solventar los problemas que genera el anterior sistema, el central, en este caso los clientes clonan completamente el repositorio, incluido su historial. Si algun servidor esta inactivo o desaparece, cualquiera de los repositorios del cliente se puede copiar en el servidor para restaurarlo.

5. Describe los siguientes comandos:
- git status: Describe el estado del directorio, su version, etc.
- git add: Mueve, y cambia los archivos seleccionados del directorio actual hacia el "staging area", te permite hacer una version antes de mandarlo hacia el historial oficial.
- git add . : Lo mismo que git add, pero lo hace con todo el directorio.
- git commit -m: Agarra la version que hiciste con "git add" y la proyecta hacia el historial.
- git log: Te deja ver las versiones anteriores del proyecto, provee informacion sobre las versiones que se mandaron anteriormente de ese repositorio.
- git push: "Empuja" los archivos modificados hacia el repositorio.




