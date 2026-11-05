# Práctica Git: resolución de conflictos con `git pull --rebase`

## Captura 1: error `! [rejected]` al hacer `git push`

![Captura 1](Imagenes2/8del5.png)

## Captura 2: marcas de conflicto en el editor

![Captura 2](capturas/captura2.png)

## Captura 3: `equipo.md` finalizado en GitHub

![Captura 3](capturas/captura3.png)

## Pregunta de reflexión

Git bloqueo mi subida porque mi compañero ya habia subido un cambio al repositorio remoto que yo no tenia en local. Si me hubiera dejado hacer el push, habria borrado su trabajo, asi que me obligo a traer primero sus cambios.

La ventaja de `git pull --rebase` es que pone mis commits encima de los del remoto y el historial queda lineal, sin el commit extra de fusión que crea un `git pull` normal.
