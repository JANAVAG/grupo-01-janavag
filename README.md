# <div align="center"> TAREA OPCIONAL </div>

## Especificaciones:
```
Hacer un script que tenga una lista de 5 mascotas: perro, gato, tortuga,pez,cobra 

```
<div align="center">

| VARIABLE     | ACTIVIDADES A REALIZAR |
|--------------|------------------------|
| PERRO        |        !GUAU!          |
| GATO         |        ¡MIAU!          |
| TORTUGA      |        "..."           |
| PEZ          |       ¡GLU GLU!        |
|COBRA         |        ¡ZZZZ!          |

</div>

### SCRIPT

<div align="center">

```
#!/bin/bash
perro(){
      for i in {1..3}; do
         echo "¡Guau!"
     done
}
gato(){
      for i in {1..3}; do
         echo "¡Miau!"
     done
}
tortuga(){
      for i in {1..3}; do
         echo "..."
     done
}
pez(){
      for i in {1..3}; do
         echo "¡gluglu!"
     done
}
cobra(){
      for i in {1..3}; do
         echo "¡ZZzzz!"
     done
}
echo "¿Que animal quieres que imite?"
read animal
echo "Tu animal es un@: $animal"
sleep 1
echo "Buscando al animal"
sleep 2
echo "---"
sleep 5
if [ "$animal" = "perro" ]
then
        perro
elif [ "$animal" = "gato" ]
then 
        gato
elif [ "$animal" = "tortuga" ]
then 
        tortuga
elif [ "$animal" = "pez" ]
then 
        pez
elif [ "$animal" = "cobra" ]
then
        cobra
else
        echo "seguimos en la busqueda"
        sleep 1
        echo "---"
        sleep 1
        echo "--"
        sleep 1
        echo "."
        sleep 1
        echo "No contamos con ese animal :( "
fi

```
</div>