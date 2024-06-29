# WSL
WSL es la abreviatura de Windows Subsistem for Linux.


### Comprobar si está instalado
Podemos probar con algunos de los siguientes codigos en la terminal de windows, si WSL se encuentra instalado

```ssh
wsl --help
```
este sirve para obtener información acerca de los comandos que se pueden usar
![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/7f0edaa2-b0d1-49d6-8237-07ef64293ca9)

Usando el comando
```
wsl --list --verbose
```
o la versión corta de este
```
wsl -l -v
```
![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/59559116-d352-4b5a-9ffe-de8b2213a862)
puedes listar la lista completa de instancias wsl en tu sistema operativo además de la versión de WSL en la que se encuentran

## Desinstalar 

### Desinstalar Unicamente una instancia
una ves que tenemos el nombre de la instancia de WSL que queremos eliminar, lo hacemos con el comando unregistred y el nombre de la misma
```
wsl --unregistred <nombre de la instancia>
```
![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/129f990c-637b-4b5e-bf4c-21d6e9ce4cf2)

### Desinstalar Completamente WSL de windows
Podemos encontrar esta opción desde el panel de control, pero es más fácil de acceder directamente desde las busquedas

Agregar o quitar características de windows

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/b02c1566-0431-4780-9c55-abf573674d68)

en el cual tenemos una lista de componentes opcionales de windows, entre los cauales tenemos que desactivar el siguiente
![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/a75bb4f6-77f8-46b8-9691-51b511ab3b2a)
posteriormente damos click a aceptar, y nos pedirá reiniciar nuestro pc
y damos en reiniciar ahora
