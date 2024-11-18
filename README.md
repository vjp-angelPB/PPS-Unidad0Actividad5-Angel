# PPS-Unidad0Actividad5-Angel
## Actividad 5 - Unidad 0 Uso de Git (III)

## Creación del repositorio
![](Images/img1.png)

## Viendo los remotos
Con `git remote -v` podemos ver los repositorios remotos que tenemos configurados.

1. Mira tus remotos.
   
![](Images/img2.png)

# Visualizando la página web

1. Visualiza con php el contenido de la página web(`php -S 0:8080`).

(No aparece nada)

2. Introduce dentro de la carpeta img una imagen de tu foto o avatar. El nombre del archivo debe de llevar como nombre tu nombre.

![](Images/img3.png)

3. Dentro de la carpeta profile crea un archivo html con el mismo nombre del archivo de la imagen que copiaste en el punto anterior.

![](Images/img4.png)

4. Lanza el comando php para que se muestre el contenido de la página web y ver cómo se ha modificado.

![](Images/img5.png)

## Colaborando
Podemos añadir colaboradores en nuestro proyecto desde la Configuración del Repositorio, apartado Collaborators. Éstos podrán realizar cambios en él.


1. Comparte tu proyecto con al menos dos compañeros.

![](Images/img8.png)

![](Images/img7.png)

3. Para cada uno de los proyectos de tus compañeros:
  * Acepta la invitación de colaboración en su repositorio.
 
  ![](Images/img6.png)
  
  ![](Images/img10.png)

  * Clona el repositorio (Recuerda que tendrás que crear una carpeta nueva para él).
 
  ![](Images/img11.png)
  
  ![](Images/img17.png)


  * Añade una nueva rama con tu nombre y cámbiate a la rama que has creado
  
  ![](Images/img12.png)
  
  ![](Images/img18.png)


  * Comprueba en que rama te encuentras (`git status` te dá la información).
 
  ![](Images/img13.png)
 
  ![](Images/img19.png)


  * Añade en esa rama tus archivos de usuario (foto y profile).
  
  ![](Images/img14.png)
  
  ![](Images/img15.png)
  
  ![](Images/img20.png)
 
  ![](Images/img25.png)
  
  * Sube los cambios de tu rama al repositorio remoto y comprueba que puedes verlos en la web.
 
  ![](Images/img22.png)
 
  ![](Images/img21.png)

  ![](Images/img27.png) 

 
Ahora vamos a hacer modificaciones en la rama main de tus compañeros. Es importante que el tiempo entre el push y el pull sea pequeño, ya que si en ese tiempo hay modificaciones por parte de otro colaborador, es posible que haya inconsistencias, en cuyo caso tendremos que utilizar `git merge`.


1. Cambiate a la rama main de los proyectos de tus compañeros

![](Images/img28.png)

![](Images/img33.png)


2. Añade en ella tus archivos de usuario (foto y profile).

![](Images/img29.png)

![](Images/img34.png)


3. Sube los cambios a la rama main de los repositorios de tus compañeros.

![](Images/img30.png)

![](Images/img35.png)


4. Vuelve a tu repositorio.

![](Images/img31.png)

5. Comprueba en qué rama te encuentras.

![](Images/img32.png)

6. Comprueba que tus compañeros hayan creado sus ramas en tu repositorio (`git branch`). Si no es así...!!!! échales una mano, hombre¡¡¡¡¡

![](Images/img.png)

![](Images/img.png)


7. Comprueba con `git diff` las diferencias existentes entre las ramas Main y las de tus compañeros

![](Images/img.png)

![](Images/img.png)


## Erre que erre con Git Logs

1. Muestra los logs

`git log`
![](Images/img.png)

2. Muestra los logs de los últimos 3 commits
`git log -n 3`
![](Images/img.png)

3. Muestra los logs utilizando el modificador --pretty
`git log --pretty=oneline`
![](Images/img.png)

5. Muestra los logs de los últimos 2 commits donde se vean las diferencias de cada una de las entradas.
`git log -n 2 -p`
![](Images/img.png)

7. Muestra los logs de las modificaciones realizadas en el último día
`git log --since="1 day ago"`
![](Images/img.png)



















































