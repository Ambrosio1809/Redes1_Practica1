# Practica1 GRUPO 9

## UNIVERSIDAD SAN CARLOS DE GUATEMALA
## FACULTAD DE INGENIERIA 
## REDES DE COMPUTADORAS 1
---------------------------------------------------------------------------
### INTEGRANTES
- ERICK VALENZUELA
- FERNANDO AMBROSIO
- AARON JUAREZ 
- SOHANY LOPEZ
---------------------------------------------------------------------------
### HERRAMIENTAS UTILIZADAS
- Equipo.
    - 4 computadores con sistema operativo libre *"windows 10 o ubuntu"*
- Software.
    - Administradors VPNs *"OpenVPN"*
- Plataforma
    - Google Cloud Plataform (GCP)
---------------------------------------------------------------------------
### DESCRIPCION DE LA PRACTICA
Creacion de una red VPN implmentado en un servicio en la nube :rocket:, logrando conectar varias computadoras :computer: a dicha red pudiendose comunicar las unas a las otras por medio de internet.

   <p>
    <img src="./red.jpg" title="hover text">
   </p>

---------------------------------------------------------------------------
### PASOS PARA CREACION DE UNA RED VPN
1. Creacion de maquina virtual
    * Para la creacion de la maquina virtual se debe contar con una cuenta de google, procedemos a ir hacia el area de *compute engine* y luego en *virtual machine* en esta area le damos en agrear nueva instancia, y nos saldra la siguiente imagen en donde podremos configurar nuestra instancia de VM, aqui podemos escoger las propiedades que queres para nuestra maquina, para la practica se utilizaron las siguiente.
        * SO: ubuntu debian.
        * Maquina virtual de 2 nucleos y 8gb de ram 
        * Acceso predeterinado
        * trafico http y https
<p align="center">
    <img src="./capturas/1.JPG" width="500" title="hover text" >
</p>

2. Arrangue de Maquina virutal
    * Para este paso solmante debemos de seleccionar la maquina virutal que creamos y darle click derecho e iniciar maquina virtual.
<p align="center">
    <img src="./capturas/2.JPG" width="500" title="hover text" >
</p>

3. Uso de maquina virtual
    * Cuando la maquina virtual y esta corriendo debemos de seleccionar la opcion que nos parece de SSH, esta opcion nos abrira una venta que es la consola del sistema operativo que escogimos en este caso seria la consola de ubuntu Debian.
    * Lo primero que debemos hacer es actualizar las libreria del sistema operativo para esto utilizamos el comando 
    ```
    npm apt-get update
    ```
    * luego de ingresar el anterior comando damos enter y esperamos a que termine de realizar las actualizaciones
<p align="center">
    <img src="./capturas/3.JPG" width="500" title="hover text" >
</p>

4. Instalacion del paquete *WGET*
    * Este paquete nos servire para poder descargar archivos a travez de una url, para poder saber si tenes instalado el paquete *wget* en nuestro sistema operativo en este caso ubuntu, debemos ingresar el siguiente comando.
    ```
    sudo wget -v
    ```
    * Si al ingresar este comando nos sale un mensaje como en la imagen que dice *command not found* debemos de instalar este paquete en nuestro sistema operativo, para esto debemos escribir el siguiente comando.
    ```
    sudo apt-get install wget
    ```
    * Al ingresar este comando y darle enter comenzara la descarga e instalacion de este paquete, tal y como se muestra en la imagen.
<p align="center">
    <img src="./capturas/4.JPG" width="500" title="hover text" >
</p>

5. Verficiar si el paquete *WGET* quedo correctamente instalado
    * Para poder verficar si el paquete quedo debidamente instalado debemos de ingresar en el siguiente comando.
    ```
    sudo -i
    ```
    * el anterior comando nos permite ser super usuarios, luego escribimos en la consola.
    ```
    wget -v
    ```
    * Tal y como se nos muestra en la imagen sabremos que todo quedo debidamente instalado.
<p align="center">
    <img src="./capturas/5.JPG" width="500" title="hover text" >
</p>

6. Instalacion de *OpenVPN*
    * texto
<p align="center">
    <img src="./capturas/6.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/7.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/8.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/9.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/10.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/11.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/12.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/12.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/13.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/14.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/15.JPG" width="250" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/16.JPG" width="250" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/17.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/18.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/19.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/20.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/21.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/22.JPG" width="500" title="hover text" >
</p>

3. texto
    * texto
<p align="center">
    <img src="./capturas/23.JPG" width="500" title="hover text" >
</p>
