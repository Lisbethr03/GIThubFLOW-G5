# FLUJO DE TRABAJO - GRUPO 5
## Integrantes
- Lisbeth Romero
- Kardelis Aquino
- Chelsy Rosario
- Paulette Cruz

## Git & Github
![image](https://user-images.githubusercontent.com/77154429/109735933-f2e15b00-7b99-11eb-9aff-42d0a1ad73d8.png)

# Tabla de Contenido
1. Introducción
2. Temas Desarrollados:
- QUE ES GIT
- GIT FLOW 
- GIT HUB FLOW
- DIFERENCIAS
3. Comandos utilizados con Ejemplos
4. imágenes relacionadas
5. Conclusión
6. Bibliografía

# Introduccion
En este trabajo hablaremos acerca de git y github. 
La gente usa GitHub para construir algunas de las tecnologías 
más avanzadas del mundo. Tanto si estás realizando visualizaciones 
de datos como programando un nuevo videojuego, existe toda una 
comunidad y un conjunto de herramientas en GitHub que pueden 
ayudarte a hacerlo todavía mejor.

# Desarrollo

## Que es GIT
Hoy en día, Git es, con diferencia, el sistema de control de 
versiones moderno más utilizado del mundo. 
Git es un proyecto de código abierto maduro y con un mantenimiento 
activo que desarrolló originalmente Linus Torvalds, el creador 
del kernel del sistema operativo Linux.
Las características básicas de rendimiento de Git son muy sólidas 
en comparación con muchas otras alternativas. 

La confirmación de nuevos cambios, la ramificación, la fusión y la comparación 
de versiones anteriores se han optimizado en favor del rendimiento. Los algoritmos 
implementados en Git aprovechan el profundo conocimiento sobre los atributos comunes 
de los auténticos árboles de archivos de código fuente, cómo suelen modificarse 
con el paso del tiempo y cuáles son los patrones de acceso.
Git se ha diseñado con la principal prioridad de conservar la integridad del código 
fuente gestionado. El contenido de los archivos y las verdaderas relaciones entre estos 
y los directorios, las versiones, las etiquetas y las confirmaciones, todos ellos objetos 
del repositorio de Git, están protegidos con un algoritmo de hash criptográficamente 
seguro llamado "SHA1". De este modo, se salvaguarda el código y el historial de cambios 
frente a las modificaciones accidentales y maliciosas, y se garantiza que el historial 
sea totalmente trazable.

# Gitflow

Git flow, que como su nombre indica, es un flujo de trabajo aplicado a un repositorio Git. [Vincent Driessen](https://nvie.com/posts/a-successful-git-branching-model/) fue el encargado de popularizarlo, definiendo un modelo estricto de ramificación diseñado en torno a los lanzamientos del proyecto. Es ideal para proyectos que lleven una planificación de entregas iterativas. Permite la paralelización del desarrollo mediante ramas independientes para la preparación, mantenimiento y publicación de versiones del proyecto así como soporta la reparación de errores en cualquier momento.

Todo proyecto, por defecto, debería tener al menos dos ramas infinitas para su desarrollo. Esta metodología define que deben existir dos ramas principales:

1.  master
2. develop

Anque también se emplean ramas de apoyo, llamadas feature branch, reléase branch y hotfix.

## GITHUB-FLOW

![Open source tool for bug hunters searches for leaked secrets in GitHub  commits | The Daily Swig](https://portswigger.net/cms/images/54/14/6efb9bc5d143-article-190612-github-body-text.jpg)
Github es lo que se denomina una forja, un repositorio de proyectos que usan Git como sistema de control de versiones. Es la forja más popular, ya que alberga más de 10 millones de repositorios. Debe su popularidad a sus funcionalidades sociales, principalmente dos: la posibilidad de hacer forks de otros proyectos y la posibilidad de cooperar aportando código para arreglar errores o mejorar el código. Si bien, no es que fuera una novedad, sí lo es lo fácil que resulta hacerlo.   Creado en 2011 por GitHub 11​ y es la forma de trabajo sugerida por las funcionalidades propias de GitHub.  Alguna de sus caracteristicas son:

-   Un wiki para documentar el proyecto, que usa MarkDown como lenguaje de marca.
-   Un portal web para cada proyecto.
-   Funcionalidades de redes sociales como followers.
-   Gráficos estadísticos.
-   Revisión de código y comentarios.
-   Sistemas de seguimiento de incidencias.

####  Seguir el flujo de GitHub 
1. Crea una rama de un repositorio.
2. Crea, edita, renombra, mueve o elimina archivos.
3. Envía una solicitud de extracción desde tu rama con tus modificaciones propuestas para iniciar un debate.
4. Realiza modificaciones en tu rama, según sea necesario. Tu solicitud de extracción se actualizará de manera automática.
5. Fusiona la solicitud de extracción una vez que la rama esté lista para ser fusionada.
6. Organiza tus ramas utilizando el botón de eliminación de la solicitud de extracción o en la página de ramas.

## Comandos utilizados en Git
![Comandos básicos de Git que debes conocer | EDteam](https://edteam-media.s3.amazonaws.com/community/original/fc43b465-dbfb-465e-9705-b38d230452fc.jpg)
![Comandos básicos de Git (Parte 2) | Tecnologias de la informacion y  comunicacion, Informatica programacion, Desarrollo de software](https://i.pinimg.com/originals/e5/5b/5f/e55b5febbeb023f3cea15ce4e015f8c0.jpg)
#### El comando  `git branch`

Hasta el momento, lo que habíamos realizado con este comando era única y exclusivamente la creación de una nueva rama con  `git branch nueva_rama`. Sin embargo, este comando nos proporciona más opciones interesantes
![Resumen de comandos de Git y GitHub - aprendiendo ingeniería](http://aprendiendoingenieria.es/wp-content/uploads/2017/07/comandos-de-git-Ramas.png)

-   Mostrar un listado de las ramas del proyecto. Para ello, ejecutaremos la orden  `git branch`. En la siguiente captura de pantalla verás el resultado de ejecutarlo. Si te fijas, delante de una de las ramas vemos un  `*` y, además, está en otro color. Esto nos indica que la rama señalada es la  **rama activa**.
-   Si ejecutamos la orden  `git branch -v`, además de esto, nos mostrará el último  _commit_  que hemos realizado.
- -   Por otro lado, tenemos la opción de conocer cuáles de las ramas presentes están fusionadas, y cuáles no. Para ello, utilizaremos las ordenes  `git branch --merged`  y  `git branch --no-merged`, para ver las ramas fusionadas y las no fusionadas, respectivamente.
-
#### Trabajando con etiquetas…

Disponemos de una serie de herramientas que nos permiten trabajar con etiquetas:

-   `git tag`  **lista**  las etiquetas existentes.
-   `git tag etiqueta`  **crea**  una etiqueta ligera llamada  `etiqueta`.
-   `git tag -a etiqueta -m "anotación"`  crea una etiqueta anotada llamada  `etiqueta`  con una anotación. Si no añades la opción  `-m`, abrirá el editor de texto que tengas configurado.
-   `git show etiqueta`  muestra los  **datos**  asociados con la etiqueta  `etiqueta`.
-   `git -s etiqueta -m "anotación"`  crea una etiqueta firmada con tu firma GPG.
-   `git tag -v etiqueta`  nos permite verificar una etiqueta. firmada. Debemos disponer de la clave GPG pública del autor para poder verificarla.

También es posible etiquetar un  `commit`  posteriormente.
#### Las etiquetas y los servidores remotos

Por último, indicar que la orden  `git push`  **no sube las etiquetas a un servidor remoto**, es necesario subirlas de forma explícita. Para ello utilizaremos alguna de las siguientes órdenes:

-   `git push origin etiqueta`  para subir una etiqueta en concreto.
-   `git push origin --tags`  para subir todas las etiquetas.


## Diferencias

**git-flow:**
En git-flow se gestionan varias ramas con objetivos 
diferentes, por ejemplo, hay una rama de desarrollo, 
una release, una o varias ramas para características, 
para parches, etc.

El flujo indica que se empieza en una o varias feature,
luego pasa a develop, luego a master y luego a release.

feature -> develop -> master -> release
Cada etapa de este ciclo lleva el mismo proceso de solicitud 
de fusión (pull request), de fusión (merge) con la rama inmediata 
siguiente.

Esto significa que cuando una feature está lista, se fusiona
con la rama de desarrollo. Una vez que están listas todas las
características deseadas para una versión (por ejemplo), la rama
de desarrollo se fusiona con la master. Al final se libera una 
nueva versión en la rama release.

**GitHub flow:**

En GitHub hay un principio sobre la rama master que dice: 
la rama master siempre funciona.

Además, hace uso de tags (un punto específico en alguna rama) 
y de una característica de release que es una instantánea de la
tag selecciona, que permite crear estas release fácilmente.

Aunque el proceso de solicitud -> revisión -> fusión existe en GitHub
Flow es más simple, porque no pasan por ramas consecutivas de desarrollo.

GitHub propone que todas las ramas de desarrollo vayan a master una 
vez aprobada y que la liberación de versiones se haga por medio de 
tags e instantáneas release.


## Imagenes relacionadas


![Git y Git Flow](https://camo.githubusercontent.com/38f113b96a368dfb7f634d2f2da97e7b8c748042d2a284b97c3fad048bb3ff55/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f323733322f312a6d74736b3366515f4252656d466964686b656c3364412e706e67)

![Git Flow](https://miro.medium.com/max/638/0*PRJYeVCeztuOuddN.jpg)



## Conclusión.


No existe un flujo de trabajo de Git universal. Como se ha indicado anteriormente, es muy importante desarrollar un flujo de trabajo de Git que suponga una mejora productiva para tu equipo. Además de la cultura de los participantes del grupo, el flujo de trabajo debe ampliar la cultura empresarial. Las funciones de Git, como las ramas y las etiquetas, deben complementar la planificación de publicación de tu empresa. Si tu equipo usa software de gestión de proyectos con seguimiento de tareas, puede que quieras usar ramas que se correspondan con las tareas en curso. Es recomendable probar, sin embargo, cada quien tiene su forma y debe ser respetada. 


## Bibliografía.



[https://cleventy.com/que-es-git-flow-y-como-funciona/](https://cleventy.com/que-es-git-flow-y-como-funciona/)

