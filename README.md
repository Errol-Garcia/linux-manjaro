
# MANJARO

Manjaro es una distribución bastante conocida.
Basada en Arch Linux, también es de lanzamiento continuo (rolling release), 
pero al contrario del sistema del que deriva, Manjaro es muy amigable con el usuario, 
tanto, que recién instalada ya trae todo lo necesario para empezar a usar Steam.
 
 # Instalacion
instalacion paso a paso de manjaro.

## 1. Descarga
Descargamos la imagen iso del SO [Manjaro][1_0] que pesa aproximadamente 3.4 Gb

![paginaWeb](img/screenshot1.png)


[1_0]:https://manjaro.org/downloads/official/xfce/ 

## 2. Maquina Virtual
Para poder instalar nuestro SO vamos a hacer uso la maquina virtual [VirtualBox][1_1]
ya que por medio de esta podemos crear un SO sobre un SO y procedemos a crear nuestra maquina virtual.


## 2.1 crear una nueva maquina virtual
Para crear una nueva maquina virtual abrimos nuestro [VirtualBox][1_1] y en la parte superior nos saldra la opcion
para lograr nuestro cometido 
[1_1]:https://www.virtualbox.org/

![screenshot2](img/screenshot2.jpg)

## 2.2 Nombre y ubicacion del SO
Organizar en que carpeta desea ubicar la maquina virtual, lo cual por defecto viene 
en una carpeta del mismo software
![screenshot3](img/screenshot3.jpg)

luego de esto presionar "Next".

## 2.3 Tamaño de memoria
Ahora nos aparece unaa ventana en la cual tenemos que asignar la cantidad de Memoria RAM le asignaremos a nuestra maquina virtual,
nos aparece una barra o una casilla para poder poner exactamente la cantidad; ay que tener en cuenta
que no podemos exagerar ni asignar poca Memoria RAM puesto que si no esta en un punto equilibrado
puede ponerse lento o nuestra maquina virtual en ejecucion o SO que tengamos originalmente en nuestro equipo
por ello es recomendable no sobrepasar el limite que nos plantea la misma maquina virtual.
![screenshot4](img/screenshot4.png)

## 2.4 Disco Duro
Nuesta maquina virtual necesita un disco duro en el que almacenara toda la informacion que manejaremos alli.
En esta pestaña nos da tres opciones, la primera nos la da para no añadir un disco duro, la segunda es para crear una disco duro
virtual y asi alli guardar informacion, la tercera y ultima opcion es por si depronto tenemos un archivo que anteriormente por ejemplo
hayamos utilizado como disco duro de otra maquina virtual y lo utilizariamos en la que estamos creando; en este caso le daremos en la segunda opcion
porque crearemos una nuevo.

![screenshot5](img/screenshot5.png )

## 2.5 tipo de archivo de disco duro
* [VDI (VirtualBox Disk Image)][2.5.1]: es la selección por defecto,es la imagen de un disco duro virtual
     o el disco lógico asociado con una máquina virtual.
* [VHD (Virtual Hard Disk)][2.5.2]: es la opción a elegir si lo que queremos es crear un disco virtual
 versátil, que podamos recuperar cualquier archivo en su interior fácilmente. Se podrá utilizar
  como unidad de almacenamiento habitual y soporta particiones de todo tipo, como cualquier otro 
  disco duro, además de varios usuarios por cada SO virtual instalado en él. Se utiliza sobre 
  todo para Microsoft Virtual PC.

* [VMDK (VirtualBox Machine Disk)][2.5.2] es el formato típico de VMWare (otro software de virtualización,
    semejante a VirtualBox). Se escogerá esta opción para contar con plena compatibilidad entre 
    VMWare y VirtualBox y poder pasar sistemas operativos virtuales entre ambos softwares
     sin mayor problema.

En nuestro caso marcaremos la primera opcion VDI y presionaremos siguiente.

![screenshot6](img/screenshot6.png)

[2.5.1]:https://www.techopedia.com/definition/10933/virtual-disk-image-vdi
[2.5.2]:https://megazona.com/software/tipos-de-archivo-de-disco-duro-virtual-en-virtualbox

## 2.6 Almacenamiento de unidad fisica del disco duro
En este punto nos pide seleccionar si queremos nuestro disco duro <b>reservado dinamicamente </b> que solo se usara espacio
en el disco fisico a medida que se llena (hasta un maximo tamaño fijo), sin embargo
no se reducira de nuevo automaticamente cuando el espacio en él se libere o el <b>Tamaño fijo</b> que puede tomar
mas tiempo para su creacion en algunos sistemas, pero normalmente es mas rapido al usarlo.

En nuestro caso utilizaremos la opcion 1 puesto que queremos una candidad especifica para nuestro SO.

![screenshot7](img/screenshot7.png)

## 2.7 Ubicacion del archivo y tamaño
En este paso ya practicamente hemos configurado la parte de almacenamiento en nuestro disco,
ahora solamente falta asisnar la cantidad de almacenamiento que queremos que este tenga y
posterior a ello la ubicacionde donde se encontrara ese archivo.

![screenshot8](img/screenshot8.png)

seleccionamos la opcion crear para crear nuestra maquina virtual. 


# 3. Configuraciones
una ves creada la maquina virtual, accedemos a las configuraciones de la misma para poder cargar nuestra
imagen iso que descargamos inicialmente; a continuacion mostraremos el paso a paso de la carfa de la imafen iso

## 3.1 Almacenamiento
En las configuraciones siempre nos salen opciones para poder modificar algo que depronto nos haga falta.

en esta ventana nos vamos al apartado de almacenamiento porque aqui es donde vamos a cargar la imagen iso
en una unidad de disco que se crea al momento de hacer el proceso del disco duro 
![screenshot9](img/screenshot9.png)

## 3.2 Selección del disco
Se selecciona el disco en la cual cargaremos la imagen

![screenshot10](img/screenshot10.jpg)

## 3.3 Busqueda
Seleccionamos en nuestros archivos la ubicación de nuestra imagen iso y la seleccionamos

![screenshot11](img/screenshot11.png)

Posteriormente le damos en "aceptar" para cconfirmar nustra configuracion
![screenshot12](img/screenshot12.png)

# Ejecutar SO
En este punto ya hemos creado y configurado nuestra maquina virtual con el SO Manjaro,
lo que sigue a continuacion es la ejecucion de de la maquina para ver si fue correctamente creada
![screenshot13](img/screenshot13.jpg)
y si es asi, se abrira un menu en la cual nos da las siguientes opciones
![screenshot14](img/screenshot14.png)
seleccionaremos la opcion "Boot with open source drivers", en este momento nos damos cuenta que 
nuestro SO fue cargado con exito, y procedemos a seleccionar esta opcion para poder tener la distribucion
completa puesto que Linux es un SO libre.

posterior a esto saldra la siguiente ventana que nos da una bienvenida al SO Manjaro 
![screenshot15](img/screenshot15.png)