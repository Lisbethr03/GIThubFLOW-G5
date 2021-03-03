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

# Desarrollo
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




