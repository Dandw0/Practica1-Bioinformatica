# Introducción a WSL
Windows Subsystem Linux (WSL)
**Kernel** ->Windows -> Se monta el SO de Linux (`Ubuntu 22.04`)
### Donde vamos a trabajar:
#### Terminal:
![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/feature.png)

#### Partes de una terminal:

    usuario@desktop:~$ <codigo> 
`~`: Este simbolo es el que cambia | ¿por que?: Señala la ubicación de nuestra carpeta de trabajo. Al inicio vamos a tener `~` que equivale a una dirección fija: `/home/user/`
En Linux el primer `/` ,hace referencia a la raiz, el cual es un caso único.
![](https://lh3.googleusercontent.com/proxy/wCbS877XnHvD_y1fZw330ZguveBPetEqXqSO1V-JB4HCiotS1rt_A_YhTzzRS3crgVqS-h7FLFJtzjdvsZ3bqTAcpuIU9A4sZbl3TRPPR-zvcvUgPtWN)
#### Comandos básicos:
**Mostar el contenido:**
   - `ls`: Muestra los archivos/carpetas presentes en el dispositivo
  -  `ls -l`: Similar al anterior, pero te da mas detalles.
  - `ls -lh`: Similar, solo que muestra el peso de los archivos en kb o mb.
  **Navegación en Linux:**
 - `cd nombre_carpeta`: Para movilizarte a la carpeta designada.
 - La tecla `Tab` sirve para hacer un autocompletado rápido, solo esta presente si existe el documento o carpeta, por ello debe aplicarse las primeras letras del documento o carpeta requerida.

 *Forma básica:*
 ``cd nombre_carpeta``

 *Forma con direcciones globales:*
   ``cd ~/documentos``
   ``cd ..``: Navegar atrás.
   ``cd documentos/UNSAAC``: Parcial, de frente a UNSAAC.
