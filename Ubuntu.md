### actualizar  e instalar aplicaciones

podemos usar el comando `apt update`, para actualizar la lista de repositorios en nuestra distro, si marca algún error se puede agregar al principio el comando `sudo`
de igual manera, podemos usar el comando `apt upgrade` para instalar las actualizaciones que encontró, e incluso enviar ambos comandos al mismo tiempo mediante la concatenacióon de ambos con `&&`
`sudo apt install && apt install`

```
# Buscar Actualizaciones
sudo apt update

# Instalar Actualizaciones
sudo apt upgrade
```

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/adfdb983-434c-4aa6-92e7-37e35dea16ab)

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/6ffc8a8d-5eea-4f2e-aefc-c8c6c7b54e4b)

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/8f4ad56a-1965-4494-9919-0da88aab7321)

al terminar, se habrán actualizado los paquetes que tenemos instalados en nuestra distro

<details>
  <summary>
    neofetch
  </summary>
  esta aplicación nos permite obetner una información más detallada acerca de nuestra distribución, la podemos instalar usando el comando
  
  ```
sudo apt install neofetch
  ```

y si durante la instalación nos pregunta si queremos continuar, ingresamos que si `y`

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/6bb7b197-c41d-475a-9620-dd3c61264438)

dejamos que la instalación continue y al final lo podemos ejecutar con el comando 

```
neofetch
```

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/05fff312-750f-410e-8ff0-29da2e6dd055)

en la cual prodemos ver los datos de nuestra instalacion y algunos componentes de la maquina virtual
</details>

<details>
  <summary>
    htop
  </summary>
    htop es una herramienta que nos permite, de manera similar a `top`, ver el estado de nuestra distro, pero de una manera más visual
    para configurarla se usa el comando 
    
```
# Instalar

sudo apt install htop

# Ejecutar

htop
```
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/7a87c83f-e0fd-4aa2-be81-41fd5ad14edc)
  
  se puede usar `ctrl+c` así como `F10` para cerrarla

</details>

<details>
  <summary>
    Vim
  </summary>
  Vim es el editor de tetos por defecto que viene integrado con algunas distribuciones, en caso de que no venga integrado, se puede instalar mediante el administrador de paquetes con el comando
  
  ```
  sudo apt install vim
  ```

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/d614f9db-a93c-4a6d-b492-7159a7ee618a)

se puede configurar la interfaz y opciones de muchas maneras, para ello se debe abrir el archivo `.vimrc` el cual se encuentra en la raiz mediante el comando `vim .vimrc`
y entre algunas configuraciones podemos ver las siguientes opciones


```
" Características de la interfaz
set history=500 " Determina la cantidad de pasos hacia atrás que almacena vim Por defecto 20
syntax enable " Activa el resaltado de sintaxis
set number " Hace que aparezca el numero de línea
set cursorline " Resalta la linea del cursor
set wildmenu " Activa el menú de autocompletado

" Características de indentacion
set autoindent " Permite la indentación automática
set expandtab " Convierte los tabs en espacios de forma automática
set tabstop=4 " Configura la tabulación a 4 espacios
set shiftwidth=4

" Paleta de colores
colorscheme peachpuf
```
![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/1e5956c8-a9c2-4516-85b9-a48dbe6ccc02)

para regresar a la ejecución de comandops, tenemos que usar el boton de `esc`

para salir de un archivo sin guardarlo, se usa el comando `:q` o `:qa!` mientras que para guardar y salir usamos `:x`

</details>

<details>
  <summary>
    zip - unzip
  </summary>
  estas utilidades son comunmente usadas por algunos otros instaladores de paquetes, por lo cual si no vienen instaladas por defecto es recomendable que los instales manualmente
  ![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/95486bde-f0ad-4d01-99b4-f3fda85a5eac)
esto se hace con ambos paquetes mediante la siguiente linea 

  ```
  sudo apt install zip unzip
  ```

</details>

<details>
  <summary>
    tree
  </summary>
  tree es una forma que nos ayuda a ver de una manera distinta los documentos que tenemos en la dirección en la que nos encontramos de una manera más visual

  ```
sudo apt install tree
```

y nos permite ver todos los archivos que tenemos een la dirección donde nos encontremos

![image](https://github.com/NoMeLlamoDante/Practicas/assets/28581163/432e12a4-42f2-4ab3-9a01-7e6e2a54ae8f)


</details>
