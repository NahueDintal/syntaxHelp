# syntaxHelp

Es una ayuda simple para sintaxis en distintos idiomas y/o programas que uso, bash, java, podman, kubernetes.

El mecanismo es simple, es un script en bash que usa ripgrep como herramienta externa, y tiene una libreria en .json con diferenciado por idioma y luego por funciones de cada uno.

La forma de uso es con:

➜ bash-help 'buscar'

Comando: apt search <término>
Ejemplo: apt search editor
Descripción: Busca paquetes que coincidan con el término.
---
Comando: dnf search <término>
Ejemplo: dnf search editor
Descripción: Busca paquetes.
---
Comando: find [ruta] [expresiones] [acciones]
Ejemplo: find /home -name "*.txt" -type f -size +1M
Descripción: Busca archivos y directorios. Filtra por nombre, tipo, tamaño, fecha, etc.
---

