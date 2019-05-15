[200~# pe
TO DO
 Crear un repositorio y un readme.md
 Crear docker-compose.yml
 Crear a tk domain
 Nginx reverse proxy
 Let's Encrypt SSL
Docker-compose.yml:
Unico documento con 3 servicios: web, erp and drive.
Incluye volúmenes, lo que permie no perder información.
Incluye puertos, que indica el puerto dentro del docker y también el que va fuera (de nuestra máquina).
Incluye dependencias, que son otros servicios que nuestro servicio necesita (por ejemplo una sql database).
Nginxe revers proxy:
Se incluye dentro de docker-compose.yml
Nos permite nombrar los puertos (para recordarlos más fácilmente).
Hemos creado un dominio llamado aps-upc.tk con un proxy obtenemos: erp.aps-upc.tk, www.aps-upc.tk and drive.aps-upc.tk.
It gives SEO (Search Engine Optimization).
Encriptamos:
Nos genera un certificado SSL, lo uqe nos asegura la consexión.
INSTRUCIONES:
Abrir terminal
Connect to ssh 0@147.83.7.160
Go to cd docker-project
Docker-compose up
Go to Internet and erp.savebirds.tk, www.savebirds.tk and drive.savebirds.tk.





# docker-project

**TO DO**

- [X]  Create repo and readme.md
- [X]  Create docker-compose.yml
- [X]  Create a tk domain
- [X]  Nginx reverse proxy
- [X]  Let's Encrypt SSL

Docker-compose.yml:

- Unique document with three services: web, erp and drive. 
- It include volumes, which permit not to lose information.
- It include ports, which indicates the port inside the docker and also the one which go outside (the one from your computer).
- It include dependences, which are other services that our service need (for example, sql database).

Nginxe revers proxy:

- It is included inside the docker-compose.yml
- It allow us to give names to the ports (so it is easier to remember them).
- We have created a domain called savebirds.tk so with proxy we obtain: erp.savebirds.tk, www.savebirds.tk and drive.savebirds.tk.
- It gives SEO (Search Engine Optimization).

Let's Encrypt

- It gives SSL certificates, so it allow secure connections.


**INSTRUCTIONS:**

1. Open Terminal
2. Connect to ssh ea0@147.83.7.156 
3. Go to cd docker-project
4. Docker-compose up
5. Go to Internet and erp.savebirds.tk, www.savebirds.tk and drive.savebirds.tk.


