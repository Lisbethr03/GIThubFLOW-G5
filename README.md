# GIThubFLOW-G5
Presentación de los integrantes del grupo
Imagen de Introductoria
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


