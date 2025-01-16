# Repaso Git

- Creo repositorio --> New repository
- Clonar un repo --> Copio <> Code --> Me voy a VS, Terminal y git clone + url
- Entrar dentro de la carpeta creada


# ¿Cómo subo a mi repo de Git un archivo que no es un Jupyter?
- En nuestro ordenador, en la carpeta que sea el repo clonado, arrastramos el archivo para meterlo
- Nos vamos a visual, abrimos esa carpeta y en la Terminal hacemos un git status: ahí nos dirá los nuevos archivos que hemos metido
- Si queremos que se guarden en nuestro repo de github, hacemos git add, commit y push.


# Problemas a la hora de hacer pull
- Guardar antes nuestros cambios, si es lo que queremos hacer
- - git checkout -- nombres archivos que tienen modificaciones --> Si no queremos guardar nuestros cambios


# Creación de ramas
- Cuando trabajéis en proyectos reales, a veces tendréis que trabajar en ramas diferentes.
- git branch --> para ver en qué rama estamos. Nosotras en nuestros proyectos siempre trabajaremos en la rama main, la principal.
- git checkout -b nombre_rama --> Para crear nueva rama y pasarnos a ella
- git push origin nombre_rama --> Para subir los cambios desde esa rama
