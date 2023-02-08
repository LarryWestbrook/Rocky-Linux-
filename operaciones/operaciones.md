## `Operaciones básicas`

Primero que nada antes de empezar a trabajar con los paquetes se debe entrar en el terminal como usuario root (sudo su).

# Actualización de la lista de paquetes.

Para actualiza la lista de paquetes en Rocky Linux , utilizaremos el comando `$yum update`

![image](https://user-images.githubusercontent.com/45163813/217208764-22c6670c-5ab8-4333-bddd-2d7ff09aaf21.PNG)

# Actualización de paquetes instalados.

Para actualizar todos los paquetes que hay instalado en nuestro sistema Rocky Linux , utilizaremos el comando `$yum upgrade`

![image](https://user-images.githubusercontent.com/45163813/217213243-823cf50d-54c7-435b-825c-081f3e32048e.PNG)

# Búscar un paquete.

Si tu quieres buscar un paquete específico por el cual te sabes el nombre del paquete, el comando es el siguiente `$yum search {package-name}`

![image](https://user-images.githubusercontent.com/114906861/217234226-909570a7-286f-4116-9bc4-4dc538efc69f.PNG)

# Averiguar si un paquete está instalado.

Para averiguar si un paquete esta instalado solo debemos poner el comando `#yum info {nombre del paquete}`

![image](https://user-images.githubusercontent.com/114906861/217235890-16099635-9270-4329-b7c4-1e2f6880b164.PNG)

# Instalar un paquete.

El procedimiento para instalar un paquete es el siguiente `#yum install {nombre del paquete}`

![instalar](https://user-images.githubusercontent.com/45163813/217525431-f338f47b-22b9-42d0-a46c-026c92213a9b.PNG)


# Borrar un paquete.
Para borrar un paquete el procedimiento es el siguiente `#yum remove {nombre del paquete}`

![borrar](https://user-images.githubusercontent.com/45163813/217527722-e21fb2fa-4a9a-4f51-82e8-164b29bc1e74.PNG)


