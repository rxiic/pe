# docker-project
**TO DO**
- [X]  Crear un repositorio y un readme.md
- [X]  Crear docker-compose.yml
- [X]  Crear a tk domain


Docker-compose.yml:

- Unico documento con 3 servicios: web, erp and drive.
- Incluye volúmenes, lo que permie no perder información.
- Incluye puertos, que indica el puerto dentro del docker y también el que va fuera (de nuestra máquina).
- Incluye dependencias, que son otros servicios que nuestro servicio necesita (por ejemplo una sql database).

Nginxe revers proxy:
- Se incluye dentro de docker-compose.yml
- Nos permite nombrar los puertos (para recordarlos más fácilmente).
- Hemos creado un dominio llamado aps-upc.tk con un proxy obtenemos: erp.aps-upc.tk, www.aps-upc.tk and drive.aps-upc.tk.

INSTRUCIONES:
- Abrir terminal
- Connect to ssh pe0@147.83.7.160
- Go to cd docker-project
- Docker-compose up
- Go to Internet and erp.savebirds.tk, www.savebirds.tk and drive.savebirds.tk.
