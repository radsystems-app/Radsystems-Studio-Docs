---
title: Requisitos del Sistema
description: Documentación Oficial
published: true
date: 2022-06-18T16:52:33.923Z
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

El requisito para desarrollar una aplicación de escritorio con Quasar, es <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/introduction" class="is-external-link">Electron</a> Al hacer clic en la plataforma de escritorio durante la publicación, Radsystems Studio ejecuta el <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/preparation" class="is-external-link"><code>quasar mode add electron</code></a> que descarga y añade los archivos necesarios a su proyecto. Puedes encontrar las configuraciones disponibles para que Quasar Desktop las utilice en el archivo quasar.config.js <a target="_blank" href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/configuring-electron" class="is-external-link">here</a>






