# GitLand
Comando básicos que considero todo desarrollador debería conocer/dominar


## Copias instantáneas, no diferencias

Otros CVS tradicionales llevan un historial de los cambios de los archivos.

![image_cvs_tradicional](https://git-scm.com/book/en/v2/images/deltas.png)


Git maneja estos como un conjunto de copias instantaneas del sistema de archivos.

![image_cvs_git](https://git-scm.com/book/en/v2/images/snapshots.png)



## Tres Estados

Git tiene tres estados principales en los que se pueden encontrar tus archivos: confirmado (committed), modificado (modified), y preparado (staged). 

* Confirmado: significa que los datos están almacenados de manera segura en tu base de datos local. 

* Modificado: significa que has modificado el archivo pero todavía no lo has confirmado a tu base de datos. 

* Preparado: significa que has marcado un archivo modificado en su versión actual para que vaya en tu próxima confirmación.

![image 3 states](https://i.stack.imgur.com/qfins.png)

Esto nos lleva a las tres secciones principales de un proyecto de Git: El directorio de Git (Git directory), el directorio de trabajo (working directory), y el área de preparación (staging area).

![image_proyect_states](https://git-scm.com/book/en/v2/images/areas.png)

![image git](https://i.stack.imgur.com/MgaV9.png)




Estos son algunos links recomendados para conocer los comandos básicos para trabajar con GIT y no caer en la frustración:

## Documentacion oficial

[A3.1 Appendix B: Comandos de Git - Configuración](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Configuración)

[A3.2 Appendix B: Comandos de Git - Obtener y Crear Proyectos](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Obtener-y-Crear-Proyectos)

[A3.3 Appendix B: Comandos de Git - Seguimiento Básico](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Seguimiento-Básico)

[A3.4 Appendix B: Comandos de Git - Ramificar y Fusionar](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Ramificar-y-Fusionar)

[A3.5 Appendix B: Comandos de Git - Compartir y Actualizar Proyectos](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Compartir-y-Actualizar-Proyectos)

[A3.6 Appendix B: Comandos de Git - Inspección y Comparación](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Inspección-y-Comparación)

[A3.7 Appendix B: Comandos de Git - Depuración](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Depuración)

Extra para crear tus Readme.md
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

[Resolving a merge conflict using the command line](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line)

[Ramas y resolución de conflictos en git](https://styde.net/ramas-y-resolucion-de-conflictos-en-git/)

[Como resolver conflictos en Git y otros errores al subir un cambio](https://www.codigonaranja.com/2017/como-resolver-conflictos-en-git-y-otros-errores-a-subir-un-cambio)
