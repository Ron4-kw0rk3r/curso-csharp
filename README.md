## Introduccion Csharp  



### Orientacion basico para el manejo del lenguaje en linux 


##### 1. Instale la "dotnet y sdk"

#### $ pacman -Ss  dotnet
#### $ pacman -Ss dotnet-sdk 

### versiones alternativas variadas entre la version 6.0 a 8.0 

### es recomendable la version actual ya sea que esto no es para construir interfaces o procesos mas amplios 
### con lo que tiene este nucleo , siendo asi procesos intermedios en linux ... 


### Mi primer programa en Csharp


### primero configure el editor  ya sea vscode o cualquiera dependiendo de la flexibilidad de configuracion

### siendo que este maneja un nucleo en el cual cada vez que sea necesario depurar debe de realizarse el debido y correspondiente debug

## Comandos 

### $ mkdir myprogram <-- (cualquier nombre a la carpeta raiz del proyecto)

### $ cd myprogram 
### $ dotnet new console 

#### en este apartado se genera varios archivos incluido algunos cuales son los binarios prestablecidos por el programa dotnet
#### el cual se tiene configurado para su correspondiente arranque con el depurador, se realizaran configuracines mas adelante.


### continuando

#### para editar el configurador de editor de codigo en vscode 
#### instalar las extenciones correspondientes para el Lenguaje Csharp(c#)

#### agregar la carpeta myprogram al editor de codigo 

#### editar el archivo .cs y agregar en el texto "hello World " -> "Hello Machine"
#### (jajaj)

#### para correr por terminal 

#### $  dotnet run "nombredel.cs" <- no es necesario el nombre del programa ya sea por que es el archivo unico a ejecutar es variable


#### o en el editor de codigo  en la barra de navegacion "ejecutar"

#### agregar configuracion <-- es automatico.

#### y se ejecuta.


#### todos los archivos generados realizan la funcion de recrear un binario instancial con ajustes para levantar el programa generado
#### no eliminar ninguna carpeta o archivo. (OJO)

 
