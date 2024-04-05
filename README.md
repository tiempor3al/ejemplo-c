# Ejemplo de repositorio para la Asignatura de Diseno de Algoritmos

## Comandos básicos
La rama principal se llama "main". Cada actividad se debe colocar en su propia rama.
Para crear una rama, se puede ejecutar un Codespace (una máquina virtual con Visual Studio Code y el compilador en C ya instalado), en la rama "main", y luego crear una rama con el nombre de la unidad y la actividad.

### Creación de una rama
```shell
git switch -c "unidad2-actividad-3"
```

Los cambios se realizan en la rama. 

### Creación del archivo main
```shell
touch main.c
```

### Compilación del archivo main
```shell
gcc main.c -out main
```

### Ejecución del archivo main
```shell
./main
```

### Agregar los cambios a la rama local
```shell
git add .
git commit -m 'Mensaje'
```

Hasta ahora, los cambios son locales (en caso de CodeSpace, los cambios están locales en la máquina virtual).
Cuando estén satisfechos con su aplicación, los cambios deben ser empujados a la rama remota, especificando un mensaje con los cambios que se realizaron:

### Empujar los cambios a la rama remota
```shell
git push origin <nombre de la rama>
```

Una vez empujados los cambios, revisen en su repositorio remoto para asegurarse de que los cambios están presentes en las ramas.

## Otros comandos útiles

### Listar las ramas (la rama actual muestra un *)
```shell
git branch
```

### Cambiar a la rama principal
```shell
git switch main
```











