# GIThubFLOW-G5
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

# Que es GIT
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

# Diferencias
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


