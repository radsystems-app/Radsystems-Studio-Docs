---
title: Requisitos del Sistema
description: Documentación Oficial
published: true
date: 2022-06-18T18:19:22.180Z
tags: 
editor: markdown
dateCreated: 2022-05-24T12:40:50.968Z
---

>  Los requisitos del Sistema pueden variar según la aplicación que desea construir
{.is-info}
# Sistema Operativo
Actualmente, Radsystems Studio sólo es compatible con el sistema operativo Windows, Windows x86/x64 (7, 8, 10, 11). 
Puede descargar el sistema operativo desde el sitio web de  <a target="_blank" href="https://www.microsoft.com/en-us/software-download/" class="is-external-link">Sitio Web de Microsoft</a>
 Para aquellos que utilicen otros sistemas operativos, tendrán que instalar una máquina virtual (VM) y luego instalar el sistema operativo Windows compatible en esa máquina virtual (VM) para poder instalar Radsystems Studio en ella.

<a target="_blank" href="https://www.virtualbox.org/wiki/Downloads" class="is-external-link">VirtualBox (MacOS, Linux, Solaris)</a>

<a target="_blank" href="https://wiki.winehq.org/Download" class="is-external-link">Wine (Linux, MacOS, Android)</a>

<a target="_blank" href="https://www.parallels.com/" class="is-external-link">Parallels Desktop (MacOS)</a>

<a target="_blank" href="https://www.vmware.com/products/fusion.html" class="is-external-link">VMWare (MacOS, Linux)</a>

<a target="_blank" href="https://www.codeweavers.com/crossover/" class="is-external-link">CrossOver (ChromeOS, MacOS, Linux)</a>

Estas son sólo algunas de las opciones que existen.

# Servidores para Desarrollo

El servidor de desarrollo recomendado para Radsystems Studio es <a target="_blank" href="https://laragon.org/download/" class="is-external-link">Laragon</a> ,Laragon le da la opción de instalar múltiples versiones de <a target="_blank" href="https://www.php.net/" class="is-external-link">PHP</a>, <a target="_blank" href="https://nodejs.org/en/" class="is-external-link">NodeJS</a>,<a target="_blank" href="https://www.python.org/downloads/" class="is-external-link">Python</a>, etc.

Actualmente RadSystems Studio soporta 4 tipos de Base de Datos <a target="_blank" href="https://mariadb.org/download/" class="is-external-link">MariaDB</a> ,<a target="_blank" href="https://dev.mysql.com/downloads/installer/" class="is-external-link">MySQL</a>,<a target="_blank" href="https://www.sqlite.org/download.html" class="is-external-link">SQLite</a>,<a target="_blank" href="https://www.postgresql.org/download/" class="is-external-link">PostgreSQL</a>,<a target="_blank" href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" class="is-external-link">MSSQL Server</a>.

### Backend Framework (API)

Los frameworks de Backend son los procesos que se ejecutan del lado del servidor

### PHP - Laravel
PHP - Laravel depende del framework Laravel 7.24, que requiere PHP 7.2.5 a 7.4.x y Composer para la gestión de paquetes. Pero si se descarga e instala el <a target="_blank" href="https://laragon.org/download/" class="is-external-link">Laragon</a>, 
con la configuración completa, usted está listo para desarrollar un proyecto de Laravel, Boostrap & jquery(PHPRad Classic).

Si eliges instalar sólo php y composer, puedes descargarlos desde los siguientes enlaces:

<a target="_blank" href="https://laravel.com/docs/7.x" class="is-external-link">Laravel 7.24</a>

<a target="_blank" href="https://www.php.net/downloads.php" class="is-external-link">PHP</a>

<a target="_blank" href="https://getcomposer.org/download/" class="is-external-link">Composer</a>

### NodeJS - Express

El framework NodeJS - Express depende de la versión 10 de NodeJS y superiores, pero se recomienda utilizar la versión 14 de NodeJS o cualquiera de las versiones <a target="_blank" href="https://nodejs.org/en/" class="is-external-link">Long Term Support(LTS)</a>
Una vez instalado, está listo para utilizar el framework de backend <strong>NodeJS - Express.</strong>

> Tenga en cuenta que, se recomienda que descargue cualquiera de las versiones dentro de: <a target="_blank" href="https://nodejs.org/en/" class="is-external-link">Long Term Support(LTS)</a>
> 
> {.is-info}
> 

> Tenga en cuenta que si utiliza la versión 16 de NodeJS y superiores, el servidor de nodos para su proyecto no se iniciará automáticamente. Se aconseja utilizar la última versión 14 de NodeJS.
{.is-warning}

### Python - Flask

El framework Python - Flask depende de Python 3, pero se recomienda utilizar
<a target="_blank" href="https://www.python.org/downloads/release/python-3810/" class="is-external-link">Python 3.8</a>

Una vez instalado, estás listo para usar el framework de backend <Strong> Python - Flask.</Strong>

### ASP .Net Core
El marco ASP .Net Core depende de
<a target="_blank" href="https://dotnet.microsoft.com/en-us/download/dotnet/3.1" class="is-external-link">.NET Core 3.1</a>
Una vez instalado, está listo para utilizar el  de backend de ASP .Net Core.


### Framework del Frontend (UI)
Son los frameworks utilizados para generar el HTML, CSS y JavaScript de los proyectos.

### Vue Quasar
El Framework Vue Quasar depende de NodeJS versión 10.18.1, Quasar CLI. Se recomienda utilizar la versión 14 de NodeJS. Después de instalar NodeJS, puedes instalar Vue Quasar CLI usando 
**npm i -g @quasar/cli**, Si no lo haces e intentas crear un proyecto, Radsystems Studio te pedirá que lo instales.
### PrimeVue

El Framework PrimeVue depende de VueJS, pero no es necesario instalar el CLI de VueJS. Sin embargo, se recomienda tener NodeJS ya instalado.

### Bootstrap JQuery
El Framework Bootstrap JQuery no tiene ningún requisito que deba ser instalado. Una vez que haya instalado
<a target="_blank" href="https://laragon.org/download/" class="is-external-link">Laragon</a>,<a target="_blank" href="https://www.apachefriends.org/download.html" class="is-external-link">XAMPP</a>, o cualquier otro servidor de desarrollo, está listo para crear proyectos de Bootstrap y JQuery.

### Plataformas de Publicación

### Plataforma de escritorio con Quasar 

El requisito para desarrollar una aplicación de escritorio con Quasar, es <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/introduction" class="is-external-link">Electron</a> Al hacer clic en la plataforma de escritorio durante la publicación, Radsystems Studio ejecuta el <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/preparation" class="is-external-link"><code>quasar mode add electron</code></a> que descarga y añade los archivos necesarios a su proyecto. Puedes encontrar las configuraciones disponibles para que Quasar Desktop las utilice en el archivo quasar.config.js <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/configuring-electron" class="is-external-link">Aquí</a>

 Plataforma móvil con Quasar📱
 Para desarrollar una aplicación móvil con Radsystems Studio, existen múltiples <a target="_blank" href="https://quasar.dev/quasar-cli-vite/developing-cordova-apps/preparation#-start-developing" class="is-external-link">requerimientos</a>que debe cumplirse antes de poder hacerlo.

- Es necesario descargar e instalar <a target="_blank" href="https://developer.android.com/studio" class="is-external-link">Android Studio</a>
- Después de instalar <a target="_blank" href="https://developer.android.com/studio" class="is-external-link">Android Studio</a>, necesitas adicionar el camino del SDK a **ANDROID_HOME** y **ANDROID_SDK_ROOT**

<br>

<img alt="add-android-sdk-root.png" src="/getting-started/add-android-sdk-root.png">
<br>

- Descargar e instalar <a target="_blank" href="https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html" class="is-external-link">JDK</a>

- Añade la ruta de instalación del JDK a ***JAVA_HOME***, de forma similar a lo que se hizo para ***ANDROID_HOME*** y ***ANDROID_SDK_ROOT***, y luego añade JDK bin(C:\program Files\Java\jdk1.8.x\bin) y JRE(C:\gram Files\Java\jre1.8.x) a la variable path.

> Por favor, utilice la ruta donde se instaló su JDK, las rutas anteriores son sólo ejemplos.
{.is-warning}

Descargar, instalar y añadir <a target="_blank" href="https://downloads.gradle-dn.com/distributions/gradle-4.10.3-all.zip" class="is-external-link">Gradle</a> a la variable del Entorno (Environment).

Puede leer más en <a target="_blank" href="https://quasar.dev/quasar-cli-vite/developing-cordova-apps/preparation#-start-developing" class="is-external-link">Documentos de Quasar acerca de requerimientos para el desarrollo móvil</a>

### Configurar las variables del Entorno (Environment)


Algunas instalaciones necesitan codificar manualmente su carpeta padre en las variables de entorno de Windows (por ejemplo, **PHP**,**Android**, **Java**,** Python** y **Pip**).

>Para localizar el panel de Variables de Entorno, haga clic en el Menú Sart, haga clic en Panel de Control, haga clic en Sistemas, haga clic en Configuración avanzada del sistema, y luego haga clic en **Variables de Entorno**


*** Por ejemplo ** *<kbd>Inicio ></kbd><kbd>Panel de Control ></kbd><kbd>Sistema ></kbd><kbd>Configuración Avanzada ></kbd><kbd>Variables del Entorno</kbd> 
<br>


<img alt="environmental-variables.png" src="/getting-started/environmental-variables.png">

Para añadir una aplicación a la **Ruta de la Variable**, haga clic en  **Ruta de la variable** de la secció**n Variables de usuario** o **Variables de sistema**, haga clic en **Editar**, luego haga clic en **Nuevo** y añada la ruta de la aplicación.
*** Por ejemplo ** *<kbd>Ruta ></kbd><kbd>Editar ></kbd><kbd>Nuevo</kbd>
<img alt="add-app-to-path.png" src="/getting-started/add-app-to-path.png">
<br>

A continuación se muestra la lista de rutas que debe introducir si no existen ya:

Añade la ruta de **XAMPP PHP** C:\xampp\php o bien localiza la ruta de tu instalación de **PHP**  y añádela.
Añade la ruta de **Python** <code> %localappdata%\Programs\Python\Python38 </code>(Esta es la ruta de mi python.exe).
Añadir la ruta de **Python Script** <code> %localappdata%\Programs\Python38\Scripts</code> (Esta es la ruta de mi pip.exe).
Añadir la ruta de **.NetCore** <code> %programfiles%\dotnet</code> (Esta es la ruta de mi dotnet.ext).

> Cuando haya terminado, haga clic en el botón Okey para guardarlo, luego reinicie su computadora si es necesario.
{.is-success}




