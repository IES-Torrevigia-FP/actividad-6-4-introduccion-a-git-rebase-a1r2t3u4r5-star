Diferencia entre merge y rebase:

git merge junta ramas creando un commit extra y se ve el historial con ramas.
git rebase mueve los commits para que el historial quede en línea, como si todo pasara seguido.

Cuándo usar cada uno:

Usaría rebase cuando estoy trabajando solo en mi rama y quiero un historial limpio.
Usaría merge cuando trabajo en equipo o cuando la rama ya está compartida.

Por qué no usar rebase en ramas compartidas:

Porque cambia el historial y los commits, y eso puede causar problemas a otras personas que ya tienen esos cambios.
