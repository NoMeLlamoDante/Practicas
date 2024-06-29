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

puedes listar la lista completa de instancias wsl en tu sistema operativo además de la **versión de WSL** en la que se encuentran

### Desinstalar
<details>  
<summary>
  Desinstalar Unicamente una instancia
</summary>

  una ves que tenemos el nombre de la instancia de WSL que queremos eliminar, lo hacemos con el comando unregistred y el nombre de la misma
  ```
  wsl --unregistred <nombre de la instancia>
  ```
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/129f990c-637b-4b5e-bf4c-21d6e9ce4cf2)
  
</details>

<details>  
<summary>
  Desinstalar Completamente WSL de windows
</summary>

  Podemos encontrar esta opción desde el panel de control, pero es más fácil de acceder directamente desde las busquedas
  
  `Activar o desactivar las características de windows`
  
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/b02c1566-0431-4780-9c55-abf573674d68)
  
  en el cual tenemos una lista de componentes opcionales de windows, entre los cauales tenemos que desactivar el siguiente
  
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/a75bb4f6-77f8-46b8-9691-51b511ab3b2a)
  
  posteriormente damos click a aceptar, y nos pedirá reiniciar nuestro pc
  y damos en reiniciar ahora

</details>

### Instalar
<details>
  <sumanry>
    Instalar mediante interfaz
  </summary>  
  Podemos encontrar esta opción desde el panel de control, pero es más fácil de acceder directamente desde las busquedas
  
  `Activar o desactivar las características de windows`
  
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/b02c1566-0431-4780-9c55-abf573674d68)

  en la lista que aparecerá a continuación buscamos el `subsistema de Windows para Linux` y la activamos
  presionamos en aceptar y nos pedirá reiniciar el equipo, cosa que aceptamos.
  
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/d547c309-abe3-45af-8649-93fe34cb55ee)

</details>

<details>
  <summary>
    Instalar una Distribución en específico
  </summary>
  usando el siguiente comando, se pueden listar las distribuciones que pueden ser instaladas mediante WSL, de las cuales puedes elegir la que requieras instalar
  para este caso usaremos la `Ubuntu 24.04 lts`
  
```
wsl --list --online
```
  
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/525fe69e-789e-4abe-824b-2c6db2d5f037)

```
wsl --install <distribución> 
```
esperamos a que se termine la descarga y la instalación

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/ec08baea-523c-4410-80b2-b34f201b3844)

nos pedirá un usuario y una contraseña

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/ae917113-7999-4bde-beb5-9ab063ac157e)

y finalmente entrará directo hasta la consola de comandos de nuestro linux como se ve en la pantalla de a continuación

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/16ccc6fc-da01-4e79-b6e0-f1f5c5e0923a)

de la cual podemos salir simplemente tecleando el comando `exit`
</details>
