# DOCKER DOOM
Primero de todo tendremos que tener instalador Docker que en el siguiente link se puede instalar: **https://docs.docker.com/engine/install/ubuntu/**  
Una vez instalado correctamente el docker tendremos que descargar el siguiente archivo:  
![image](https://user-images.githubusercontent.com/91737963/173227422-25ff751e-3b82-42b3-9026-f9a4e3ec4ae5.png)  
Acto seguido tenemos que acceder a docker con el comando <code>sudo newgrp docker</code>, después introducir el siguiente comando <code>for i in {1..2} ; do docker run -d -t ubuntu:14.04; done</code>  
![image](https://user-images.githubusercontent.com/91737963/173227708-fd92f98f-9fcf-4822-9801-c2bbc1bf5f4e.png)  
Una vez ejecutado todo esto tendremos que descomprimir el archivo descargado anteriormente y una vez descomprimido, después tendremos que usar el siguiente cmd <code>./dockerdoomd</code>
![image](https://user-images.githubusercontent.com/91737963/173227970-6ffb6e52-0ef6-4018-b8db-f94acc540bf7.png)  
![image](https://user-images.githubusercontent.com/91737963/173228003-7ffb8fed-f929-4d15-855d-c1e77f24226b.png)  
En la última imagen se ve el puerto que es 5900. Una vez obtenido esa información tendremos que descargar **VNC VIEWER**  
![image](https://user-images.githubusercontent.com/91737963/173228027-261362e8-cd65-4ead-bfc8-026da0e6032e.png)  
Acontinuación creamos una nueva conexion e introducimos en el localhost 'localhost:5900' y como nombre introducimos el que queramos en mi caso introduci 'docker-doom'  
![image](https://user-images.githubusercontent.com/91737963/173228264-fa223b03-42b5-48e6-b642-92e7b80017dc.png)  
La clave por defecto '1234'  
![image](https://user-images.githubusercontent.com/91737963/173228095-d46cf93d-9f08-45dc-8a6d-cfee725161b8.png)  
Y listo ya esta ejecutandose  
![image](https://user-images.githubusercontent.com/91737963/173228118-6f93607a-c372-4663-b9f2-06536c8966e0.png)
