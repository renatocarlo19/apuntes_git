### git log
Muestra el historial de commits

`git log --pretty=format:%h - %an, %ar : %s`
Muestra el historial con el formato que indicamos.

`git log --oneline`
Muestra el historial en una sola línea.

`git log --graph`
Muestra el historial en un esquema de ramas.

`git log --oneline --graph`
Muestra el historial en una sola línea en un esquema de ramas.

`git log -n`
Muestra los últimos n commits

`git log --after="2019-12-17 00:00"`
Muestra el historial después de la fecha y hora indicada

`git log --before="2019-12-17 00:00"`
Muestra el historial antes de la fecha y hora indicada
