

¿QUÉ ES HUGO?
===
Hugo es un generador de sitios estáticos 

Instalación Hugo en Windows
===
Para instalar la ultima versión de Hugo en Windows lo primero que deberemos hacer es ir al siguiente link.

LINK A LA PAGINA DE DESCARGA
===
https://github.com/gohugoio/hugo/releases

Cuando abramos el link descargaremos la ultima versión que tenga un nombre parecido a hugo_extended_x.x.x_windows-amd64.zip .

Extraeremos el zip y  movemos el archivo Hugo.exe  a la ruta C:\Hugo\bin la cual crearemos.

Vamos al panel de control--> propiedades del sistema--> y clickamos en variables de entorno.

En la lista que nos mostrará buscaremos la variable PATH, y al final de esta añadiremos ‘;C:\Hugo\bin’, con esto reiniciando el sistema tendremos hugo instalado y ya lo podremos iniciar.

Instalación Hugo en Linux
===
Comprobamos si tenemos instalado snap

```snap version```

Este nos debería dar una respuesta como la siguiente:

```snap    2.55.3+22.04
snapd   2.55.3+22.04
series  16
ubuntu  22.04
kernel  5.15.0-48-generic
```
Si nos sale algo como lo de arriba significará que lo tenemos instalado y podremos continuar
Instalar el paquete hugo-extended
Utilizando el gestor Snap vamos a instalar el paquete hugo-extended.

```snap install hugo --channel=extended```