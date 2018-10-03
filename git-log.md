### git log
Muestra el historial 
` git log--pretty=format:"%h - %an, %ar:%s" 
`
Muestra la salida del historial con el formato que indiquemos 
### limitar la salida del historial
`git log -n`: cambiamos la n por cualquier numero entero, por ejemplo `git log -2` nos mostrará los 2 commits mas recientes

`git log --after "2018-10-03 00:00:00"`: Muestra los commits realizados despues de la fecha especificada

`git log --before"2018-03-10 11:20"`:Muestra los commits realizados antes de la fecha especificada

las banderas del comando `git log` se pueden usar juntas segun convenga, por ejemplo:  git log --pretty=format:"%h - %an, %ar:%s" --before "2018-10-03 09:40:00" --after "2018-10-01 20:00"
