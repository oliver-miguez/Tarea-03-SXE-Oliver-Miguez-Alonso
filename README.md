# Tarea 03 SXE
## Oliver Miguez Alonso

## Tareas a realizar: 
### 1. Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo
Primer paso a seguir será dentro de la consola en mi caso windows, porque lo ejecute en windows ejecutar el siguiente comando:
  
  docker pull alpine
  
![Imagen1](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/1.png)

Y para verificar que se encuentra en nuestro equipo ejecutamos:

  docker ps -a
  
![Imagen2](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/2.png)


### 2. Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre
Para crear un contenedor sin nombre ejecutamos el siguiente comando : 

  run alpine
  
![Imagen3](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/3.png)

Y veremos como se crea un contenedor con un nombre generado automaticamente por docker

### 3. Crea un contenedor con el nombre 'dam_alp1'. ¿Como puedes acceder a él?

A través del siguiente comando: 

![Imagen4](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/4.png)

Creamos el contenedor dam_alp1 y usamos el infinity para que estea ejecutandose constantemente para las pruebas que realizaré a continuación

Y para acceder a el simplemente ejecutamos : 

![Imagen5](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/5.png)

Y si vemos el "#" es que nos encontraremos ya dentro del el

## 4. Comprueba que ip tiene y si puedes hacer un ping a google.com

Para comprobar la ip que tiene simplemente ejecutamos esto:

![Imagen5](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/6.png)

De esta manera sabremos cual es su ip, y para hacer ping  con google.com necesitamos primero acceder al contenedor y ejecutar : 

![Imagen6](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/7.png)

### 5. Crea un contenedor con el nombre 'dam_alp2'. ¿Puedes hacer ping entre los contenedores?

Al igual que dam_alp1, creamos dam_alp2, obtenemos de igual forma su ip, y ahora dentro de este , hacemos un ping a la ip del contenedor dam_alp1:

![Imagen 7](https://github.com/oliver-miguez/Tarea-03-SXE-Oliver-Miguez-Alonso/blob/main/8.png)

### 6. Sal del terminal, ¿que ocurrió con el contenedor?

### 7. ¿Cuanta memoria en el disco duro ocupaste?

### 8. ¿Cuanta RAM ocupan los contenedores? ¿Hay algún comando docker para saber esto?.
