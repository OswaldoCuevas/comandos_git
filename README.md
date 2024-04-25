## comandos_git
### archivos que ha modificado un usuario
#### git log --author="correo" --name-only --pretty=format: | sort | uniq

### archivos con la diferencia de dos ramas
#### diff --name-status rama1 rama2

### archivos que se modificaron dado dos commits
#### git show --name-only --pretty=format: hash_inicio..hash_fin | sort | uniq

### ver cuando se modificó el archivo ye le commits que se realizó
#### git log --follow --pretty=format:"%ad - %h - %s" --date=short -- archivo
