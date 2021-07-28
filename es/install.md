---
title: Instalar RadSystems Studio
description: Documentación Oficial
published: true
date: 2021-07-28T21:30:35.273Z
tags: instalar, install
editor: markdown
dateCreated: 2021-07-14T18:49:59.914Z
---

# Instalar RadSystems Studio

Para comenzar con la instalación, debemos tomar en cuanta varias herramientas, frameworks, entre otras cosas que vamos a necesitar instalar antes de la instalación completa de RS Studio.

Iremos paso a paso con la instalación suponiendo que trabajaremos solo con proyectos Web, en otros apartados iremos viendo que instalar para publicar aplicaciones móviles como Android e iOS.

### **Paso 1**

Debemos instalar un servidor web Apache compatible con PHP, en este caso lo haremos con Laragon, ustedes pueden usar Xampp o Wampp, con el que se sientan más cómodos. Nos dirigimos al siguiente enlace [https://laragon.org/download/](https://laragon.org/download/) descargamos la versión mas reciente y estable. Si en caso quieren usar Xampp en vez de Laragon, pueden descargarlo desde [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html) y de igual forma eligen la versión más reciente. No entraremos en muchos detalles con la instalación de ambos programas ya que hay ya muchos tutoriales que pueden buscar en youtube en su idioma.

![](/pages/install/install_laragon.png)

Instalación de Laragon

### Paso 2

Una vez Laragon esté instalado, procedemos a iniciar Laragon, iniciamos todos su servicios para poder instalar Radsystems junto a nodejs.

![](/pages/install/start_laragon.png)

### Paso 3

Instalamos Node JS antes de RadSystems para una instalación más rápida, ya que como veremos más adelante necesitaremos Quasar CLI. Por tanto nos dirigimos a [https://nodejs.org/en/download/](https://nodejs.org/en/download/) y descargamos la última versión estable de node js. Una vez descargado el instalador, nos dirigimos a instalar de forma normal.

![](/pages/install/install_nodejs.png)

Revisamos que la instalación esté correcta desde el símbolo del sistema usando el comando "cmd". Una vez estando allí, ingresamos el comando **npm -v** Si el sistema responde con el número de versión de nodeJS, quiere decir que la instalación fue exitosa.

![](/pages/install/try_nodejs.png)

### Paso 4

Una vez que ya tengamos instalado todo lo anterior, procedemos a configurar dos variables de entorno para que nuestros proyectos puedan compilarse adecuadamente. Veamos paso a paso mediante imágenes cómo hacerlo.

Primero Busquemos las opciones avanzadas del Sistema de Windows, nos aparecerá de esta forma:

![](/pages/install/variables_de_entorno.png)

Seleccionamos la opción de Variables de Entorno y luego nos vamos al panel de “Variables del Sistema”, elegimos Path y damos en Editar.

![](/pages/install/variables_de_entorno_path.png)

Como verán ya agregué las rutas donde tengo instalado tanto PHP y nodejs, ustedes deben buscar la ruta donde instalaron cada programa y agregan esas rutas usando el botón nuevo.

![](/pages/install/variables_de_entorno_node_php.png)

Después de agregar las rutas a la variable de entorno **PATH**, le damos **Aceptar** a todas las ventanas para que se apliquen los cambios.

### Paso 5

Procedemos a instalar sin problemas RadSystems, hacemos una instalación normal y al finalizar nos pedirá que instalemos Quasar CLI, por lo que presionamos el botón de instalación y como ya tenemos instalado nodeJS, Quasar se instalará sin ningún problema.

Esperamos a que acabe de descargar e instalar todos los archivos necesarios y estaría listo RadSystems para usarlo y empezar a publicar nuestros proyectos, en la codificación que prefiramos, ya sea Laravel, VueJS, NodeJS o Python.