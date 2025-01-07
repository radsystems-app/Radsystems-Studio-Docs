---
title: Páginas
description: Aprenda como crear y administrar páginas en RadSystem Studio
published: true
date: 2025-01-07T00:52:22.773Z
tags: 
editor: markdown
dateCreated: 2022-06-23T20:30:17.934Z
---

Las páginas de RadSystem Studio son el núcleo del desarrollo de aplicaciones. El panel de páginas se divide en cuatro secciones:
* Tablas de la base de datos
* Páginas de tablas
* Campos de la página de la tablas
* Propiedades de la páginas de las tablas

# Sección Tablas de las Base de Datos
![data-tables-section.png](/pages/data-tables-section.png){.align-center}
1. Según el gráfico, en la parte izquierda del panel se encuentra el acceso directo a las tablas de la base de datos del árbol, además de las vistas creadas. También puedes crear tus propias vistas.
2. Hay un menú de tres botones. el primero le permite cambiar los detalles de la conexión a la base de datos.
3. El siguiente botón le permite gestionar la base de datos. A través de la interfaz, puedes añadir, duplicar o eliminar tablas y, para cada tabla, puedes gestionar los campos, así como el tipo de campo, el tamaño y otras propiedades.
4. El último botón sincroniza la base de datos actualizando todos los cambios que se han producido a través del gestor de la Base de Datos.

# Sección Páginas de Tabla
Por defecto, RadSystem Studio crea interfaces (páginas) para gestionar cada tabla de la Base de Datos. Lo que generalmente se conoce como CRUD (Create, Read, Update and Delete), se puede ver en 5 páginas: Una para listar los registros, una para ver los detalles de cada registro, una para Añadir Registros, una para Editar Registros y, finalmente, una para Eliminar un Registro.
![table-pages-section.png](/pages/table-pages-section.png){.align-center}
La Sección también ofrece tres botones para gestionar las páginas:
1. El primer botón de la sección permite añadir una página personalizada al proyecto. Entre las opciones de la ventana, podemos elegir el nombre de la página, el tipo de página (Lista, Añadir, Editar o Ver). Si tenemos configurado un menú, también podemos elegir si el acceso directo a crear es un submenú del principal o si se crea como un acceso independiente en el menú principal.
2. El segundo botón permite duplicar la página seleccionada.
3. También hay un botón para acceder directamente al diseño de la página.

En la parte inferior tenemos acceso a cada una de las propiedades que se pueden aplicar a una determinada página.
### <span style="color:blue">Para la *"Página formato lista "*, podemos configurar las siguientes propiedades:</span>

## Subsección 01 - Diseño de la página
**AjaxPage**: Permite establecer si la página utilizará la técnica de JavaScript asíncrono, procesando cualquier petición al servidor en segundo plano.
> Para habilitar la búsqueda Ajax en la lista, es importante poner en True esta opción.
{.is-info}

**Título de la página**: Por defecto, RadSystems Studio utiliza el nombre de la tabla como nombre de la página. Esta opción le permite personalizar el nombre del título que aparecerá en la página de la lista.
* **Tipo de Presentación**: Puede seleccionar cómo se presentan los datos. Elija entre un formato tabular o una cuadrícula.
**Mensaje de registro vacío**: Permite personalizar el mensaje cuando no hay datos en la tabla.

## Subsección 02 - Configuración de la consulta por defecto
* **Join Tables**: Aquí puede especificar su propia consulta SQL o acceder a una ventana que le ayudará en su construcción.
* **Where**: La opción permite especificar la cláusula SQL WHERE que permite recuperar un conjunto de datos bajo una condición.
* **Having**: La opción permite especificar la cláusula SQL HAVING que permite recuperar un conjunto de datos bajo una condición SUM o MAX.
* **Order by**: Puede especificar si la consulta se ordena de forma ascendente o descendente y los campos a los que se aplica.
* **Límit**: Permite especificar el número de registros a mostrar por bloque de páginas.
## Subsección 04 - Edición en línea
* **Edición en línea**: Permite especificar si es posible editar los registros de la misma lista.
* **Edit FieldControlType**: Permite elegir si la edición inline se basará en lo configurado en la página de Edición o a través de un formato de datos específico.
* **Use PopOverDisplay**: Le permite activar o desactivar la pantalla emergente para la edición en línea.
* **Colocación**: La opción le permite especificar la posición de la pantalla emergente en una edición en línea.
* **Modo de activación**: Puede especificar el método por el que se activa la edición en línea.
* **Mostrar Botones**: Permite especificar la posición de los botones que permiten la edición enlínea.
## Subsección 05 - Componentes de la página
* **ActionButtonDisplayStile**: Permite especificar si para ver, editar o eliminar un registro se utilizarán iconos o un menú desplegable.
* **ActionButtonInFront**: Permite seleccionar si los botones de acción estarán delante de cada fila de registros o al final de los mismos.
* **Botón Borrar**: Seleccione si el botón de borrar registros será visible.
**Botón Editar**: Seleccione si el botón de Editar registro será visible.
**Botón Ver**: Seleccione si el botón de Ver registro será visible.
* **EditButtonText**: Permite personalizar la leyenda del botón Editar.
* **VerBotónTexto**: Le permite personalizar el título del botón Ver.
* **DeleteButtonText**: Permite personalizar el título del botón Borrar.
* **Exportar**: Especifica si el selector de exportación estará presente en la vista de la lista de registros.
**Configuración de la exportación**: En la ventana emergente, puede configurar los formatos de exportación que estarán disponibles, así como especificar una plantilla personalizada o definir la orientación de la página para la exportación, entre otras opciones.
**Texto del botón de exportación**: Permite personalizar la leyenda del botón Exportar.
* **ImportData**: En la ventana emergente, puede establecer si el botón de importación de datos estará disponible, definir el selector de texto o el signo utilizado para definir la separación de campos en una importación de datos CSV.
* **Texto del botón de importación**: Permite personalizar la leyenda del botón de importación.
* **SecuenciaDeLista**: Especifica si una secuencia de lista estará presente en la vista de lista de registros.
**Incluir casilla de verificación**: Especifica si habrá una casilla de verificación para cada registro en la vista de lista.
**Paginación**: Especifica si el selector de número de página estará presente en la vista de lista de registros.
**Configuración de la paginación**: Aquí puede establecer el estilo de paginación, así como establecer si el contador de registros, el contador de páginas y el selector de registros por página serán visibles.
## Subsección 06 - Página Modal
* **EdiciónModal**: Permite establecer si la edición modal estará disponible.
* **VistaModal**: Permite establecer si la vista modal estará disponible.
## Subsección 07 - Diseño de Tablas
* **TableBorderStyle**: Le permite establecer el estilo del borde de la página de la lista.
* **Table Stripped**: Permite establecer si la lista de registros será dividida visualmente mediante líneas de separación.
* **Table Dark**: Permite aplicar un tema oscuro a la tabla de registros.
* **Table Compact**: Permite establecer un formato compacto para la página de la lista.
* **Table HeaderBackground**: Aquí puedes seleccionar, en formato bootstrap, el estilo del color de fondo de las cabeceras de los campos.
* **Table HeaderTextColor**: Aquí puede seleccionar, en formato bootstrap, el color del texto de las cabeceras de los campos.
**TableHoverable**: Permite establecer si la función de selección de registros al pasar el ratón estará disponible.
**Table Responsive**: Permite establecer si la función Responsive de la tabla estará disponible.
**Alineación de las celdas de la tabla**: Permite establecer la alineación de los datos en las celdas.

### <span style="color:blue">Para la *"Vista de Página"*, nosotros podemos configurar las siguientes propiedades:</span>

## Subsección 01 - Diseño de la página
* **AjaxPage**: Permite establecer si la página utilizará la técnica de JavaScript asíncrono, procesando cualquier petición al servidor en segundo plano.
* **Título de la página**: Esta opción permite personalizar el nombre que aparecerá como Título en la página de Vista.
* **Tipo de visualización**: Aquí puede establecer si el diseño de cada registro y sus títulos será horizontal o vertical.
## Subsección 02 - Configuración de la consulta
**Join Tables**: Le permite especificar su propia consulta SQL o acceder a una ventana que le ayudará en su construcción.
## Subsección 02 - Registro de Eventos
* **Configuración de la Acción de Correo**: Aquí puede establecer si se enviará un correo electrónico cada vez que se muestre el registro, así como el título, el asunto y el origen del correo.
> Asegúrese de haber establecido la configuración de correo por defecto en la opción de configuración del proyecto.
{.is-warning}
## Subsección 03 - Componentes de la página
* **EditButton**: Seleccione si el botón Editar registro será visible.
**Botón Borrar**: Seleccione si el botón de Borrar registro será visible.
* **EditButtonText**: Permite personalizar la leyenda del botón Editar.
* **ModalEdit**: Permite establecer si la edición modal estará disponible.
* **DeleteButtonText**: Permite personalizar el título del botón Eliminar.
* **Exportar**: Le permite establecer si el selector de exportación estará presente en el registro de la vista.
* **Configuración de la exportación**: En la ventana emergente, puede configurar los formatos de exportación que estarán disponibles, así como especificar una plantilla personalizada o definir la orientación de la página para la exportación, entre otras opciones.
**Texto del botón de exportación**: Permite personalizar la leyenda del botón Exportar.

### <span style="color:blue">Para *"Agregar Página"*, nosotros podemos configurar las siguientes propiedades:</span>
## Subsección 01 - Diseño de la página
* **Título de la página**: Esta opción permite personalizar el nombre que aparecerá como Título en la página de Añadir.
* **SubmitButtonText**: Permite personalizar la leyenda del botón Añadir.
* **EnableCaptchaValidation**: Le permite establecer si la validación Captcha estará disponible antes de añadir un registro.
**PageCustomValidation**: Le permite colocar su propio código para validar cuando se inserta un nuevo registro.
* **HabilitarCampoAutocompletado**: Seleccione si la función de autocompletar estará disponible.
**SubFormas**: Esta función permite añadir subformularios al añadir un registro. Puede especificar el tipo de relación, el nombre del formulario secundario y la clave anterior.
**Tipo de diseño del formulario**: Le permite seleccionar el diseño del formulario.
## Subsección 02 - Generalidades
* **MensajeDespuésDeAñadir**: Permite personalizar el mensaje que se mostrará una vez añadido un registro.
## Subsección 02 - Eventos de registro
* **Redirect To After Add**: Permite establecer la página a la que se redirigirá una vez añadido el registro.
* **Configuración de la Acción de Correo**: Aquí puede establecer si se enviará un correo electrónico cada vez que se añada el registro, así como el título, el asunto y el origen del correo.
> Asegúrese de haber establecido la configuración de correo por defecto en la opción de configuración del proyecto.
{.is-warning}
## Subsección 03 - Componentes de la página
* **Configuración del indicador de carga**: Aquí puede establecer el estilo de paginación, así como establecer si el contador de registros, el contador de páginas y el selector de registros por página serán visibles.

## <span style="color:blue">Para la *"Página Editar"*, nosotros podemos configurar las siguientes propiedades:</span>
## Subsección 01 - Diseño de la página
* **Título de la página**: Esta opción permite personalizar el nombre que aparecerá como Título en la página de Edición.
* **SubmitButtonText**: Permite personalizar la leyenda del botón Editar.
* **EnableCaptchaValidation**: Le permite establecer si la validación Captcha estará disponible para un registro editado.
**PageCustomValidation**: Le permite colocar su propio código para validar cuando se edita un registro.
## Subsección 02 - General
* **FormLayoutType**: Le permite seleccionar el diseño del formulario.
* **MensajeDespuésDeAñadir**: Permite personalizar el mensaje que se mostrará una vez editado un registro.
## Subsección 02 - Eventos de registro
* **Redirect To After Add**: Permite establecer la página a la que se redirigirá una vez editado el registro.
* **Configuración de la Acción de Correo**: Aquí puede establecer si se enviará un correo electrónico cada vez que se edite el registro, así como el título, el asunto y el origen del correo.
> Asegúrese de haber establecido la configuración de correo por defecto en la opción de configuración del proyecto.
{.is-warning}
## Subsección 03 - Componentes de la página
* **Configuración del indicador de carga**: Aquí puede establecer el estilo de paginación, así como establecer si el contador de registros, el contador de páginas y el selector de registros por página serán visibles.

### <span style="color:blue">Para *"La Página Borrar"*, nosotros podemos configurar las siguientes propiedades:</span>
## Subsección 01 - General
* **PromptMessageBeforeDelete**: Aquí puedes personalizar el mensaje que se muestra antes de borrar un registro.
* **PromptDisplayStyle**: Permite establecer el estilo del mensaje que se muestra.
* **Redirect To After Delete**: Permite establecer la página a la que se redirigirá una vez eliminado el registro.
## Subsección 02 - General
* **Configuración de la acción del correo electrónico**: Aquí puede establecer si se enviará un correo electrónico cada vez que se elimine el registro, así como el título, el asunto y el origen del correo.
> Asegúrese de haber establecido la configuración de correo por defecto en la opción de configuración del proyecto.
{.is-warning}

> Para una explicación de la columna "Editar Código" , por favor siga este link [link](/es/custom-code/pages)
{.is-info}

# Sección Campos de las páginas de la tabla
## Campos de la página de la lista
![table-page-fields-section.png](/pages/table-page-fields-section.png)
En esta sección, la primera columna está formada por 5 tipos de botones:
1. Los dos primeros botones permiten reordenar los campos para su representación en la página.
2. Se abre una nueva ventana que permite introducir una expresión, un alias y el nombre del campo. Puede introducir una expresión de la lista de ejemplos o crear la suya propia.
![custom-field-editor-window.png](/pages/custom-field-editor-window.png)
3. Puede editar el campo personalizado.
4. Puede eliminar el campo personalizado.

Las siguientes columnas de la sección le permiten:

5. Las casillas de verificación de la columna OUTPUT definen si el campo se renderizará en la vista final de la página.
6. Las casillas de la columna BÚSQUEDA definen si los campos serán buscados en la vista final de la página.

En la sección también podemos definir el operador lógico SQL LIKE y los comodines para la búsqueda.

## Campos de la Página-Vista
![view-page-fields-section.png](/pages/view-page-fields-section.png)
En esta sección, para los campos de la página de visualización, puede encontrar los mismos botones para reordenar y dar salida a un campo y para añadir, editar y eliminar un campo personalizado.
## Campos de la Página-Adicionar
![add-page-fields-section.png](/pages/add-page-fields-section.png)
En este caso, para los campos de la página de adición, puede reordenar los campos y gestionar la salida de los campos en la página de adición o de edición del registro. 
## Campos Página-Editar
![edit-page-fields-section.png](/pages/edit-page-fields-section.png)
En el caso de los campos de Editar-Página, puede encontrar las mismas opciones que en la sección de campos de Añadir-Página.
# Sección de propiedades de los campos

En esta sección, las propiedades de un campo dependerán del tipo de campo que se elija. En RadStudio System hay 7 tipos de campos:
 
 * PlainText
  * Image
  * StarRating
  * ProgressBar
  * CheckButton
  * RelativeDate
  * Custom

### <span style="color:blue">Propiedades para el tipo *PlainText* </span>

![plaintext-field-properties.png](/pages/plaintext-field-properties.png)
En la vista, por ejemplo, el campo de tipo PlainText nos permite:
## Subsección 01 - Visualización
* **Sortable**: Si se establece como TRUE, se añadirá a la vista de la página un control que permitirá ordenar la columna por este campo.
* **Enlace al campo**: Por defecto, el sistema establece un acceso directo a la vista del registro con la opción --CurrentRecordDetail--. También podemos elegir entre un acceso directo a las categorías, al expediente, al valor de búsqueda, a un correo electrónico o a un teléfono, así como a las páginas para añadir o listar las páginas que hayamos creado.
   - **--CurrentRecordDetails--**: Redirige el registro de un campo a una página de detalles o a una página de visualización.
    - **--CurrentFieldCategory--**: Filtra el registro en función del campo.
    - **--CurrentFieldvalue--**: Se utiliza para vincular los datos de un campo concreto a un archivo o a un adjunto.
    - **--CurrentFieldValueSearch--**: Se utiliza para buscar en el campo actual. 
    - **--CurrentFieldMailTo--**: Añade el enlace mailto a los datos del campo actual.
    - **/menuexample/list**: Se utiliza para enlazar el registro o los datos del campo actual con la página de la lista.
    - **/menuexample/add**: Se utiliza para enlazar el registro o los datos del campo actual con la página de adición.
**FormatRecordField**: Esta propiedad también depende del tipo de campo que se elija. Para el ejemplo, a través de esta propiedad, podemos establecer el formato de fecha o moneda, formatear un STRING para que todo esté en mayúsculas o minúsculas o convertir un tipo de dato numérico a Letras entre otras opciones.
	  - **fecha_humana:** convierte el registro del campo actual en una fecha legible para los humanos.
	  - **human_time**: convierte el registro de campo actual en hora legible para los humanos.
	  - **human_datetime**: convierte el registro de campo actual en fecha y hora legibles para el ser humano.
	  - **relative_date**: convierte el registro del campo actual en una fecha relativa, por ejemplo, hace unos segundos.
	  - **to_currency('en_US')**: convierte el registro del campo actual en moneda.
	  - **ucwords**: convierte a mayúsculas la **primera letra**r de cada palabra del **registro de campo** actual o de los datos.
	  - **ucfirst**: convierte a mayúsculas la primera letra de cada cadena del registro de campo actual.
	  - **strtolower**: convierte a minúsculas el registro de campo actual.
	  - **strtoupper**: convierte el registro de campo actual en mayúsculas.
	  - **str_truncate(50,'...')**: intercepta la longitud de los datos del registro de campo actual, hasta el valor especificado.
	  - **aproximate(2)**: Aproxima los datos del registro de campo actual según el valor especificado.
	  - **a_número**: formatea los datos en un registro de campo actual. Por ejemplo: **1988665545 a 1.988.665.545**.
	  - **number_to_words('es')**: formatea los datos de un registro de campo actual a palabras. Por ejemplo: 1 2 3 4 a "uno dos tres cuatro".
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
![field-footer-expression-window.png](/pages/field-footer-expression-window.png)
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.
## Subsección 02 - Relación de detalles maestros
* **Página de detalle del registro**: Establece las características de una relación entre las tablas maestra y de detalle.
	* **Tipo de Relación**: Puede seleccionar entre una relación uno a uno o uno a varios.
	* **Tabla maestra**: Establece la tabla maestra y el campo definido como clave primaria.
	* **Tabla de detalle**: Aquí puede elegir la tabla de detalle y el campo relacionado.
	* **Aplicar a páginas**: Las casillas de verificación permiten establecer si la relación se aplicará a la vista de detalle del registro, a la página de añadir un registro o a ambas.
  ![master-detail-relation-window.png](/pages/master-detail-relation-window.png)
 	* **Visualización de la página**: Permite seleccionar la tabla que se incorporará como detalle de la relación y el estilo de su visualización (modal, online, popover o como enlace).
	* **Campo de visualización del registro / Texto**: Aquí puede establecer el texto que se mostrará en cada registro relacionado. Puede configurarlo para que muestre el valor del registro o un valor específico de los campos de la tabla.
	* **Icono de visualización**: De acuerdo con la configuración original, puede elegir el icono que se mostrará en cada registro relacionado.
	* Color del botón: En el formato boostrap, se puede seleccionar el color del botón que da acceso a la vista de la tabla de detalle.
## Subsección 04 - Edición en línea
Si la opción de edición en línea está habilitada en la asignación de propiedades de la página, aquí puede especificar si esta opción estará disponible para cada campo individualmente.
* **Edición en línea**: Establezca en TRUE para habilitar la edición en línea del campo.
**Edición en línea**: Permite elegir si la edición en línea se basará en lo configurado en la página de Edición o a través de un formato de datos específico.
* **UsePopoverDisplay**: Le permite activar o desactivar la pantalla emergente para la edición en línea.
* **Colocación**: La opción permite especificar la posición de la pantalla emergente en una edición inline.
* **Modo de activación**: Puede especificar el método por el que se activa la edición en línea.
* **MostrarBotones**: Permite especificar la posición de los botones que permiten la edición inline.
### <span style="color:blue">Propiedades del tipo *Imagen*</span>
![image-field-properties.png](/pages/image-field-properties.png)
## Subsección 01 - Pantalla
* **Enlace de campo**: Se utiliza para vincular un registro de campo particular a una página.
    - **--CurrentRecordDetails--**: Redirige el registro de un campo a una página de detalles o a una página de visualización.
    - **--CurrentFieldCategory--**: Filtra el registro en función del campo.
    - **--CurrentFieldvalue--**: Se utiliza para vincular los datos de un campo concreto a un archivo o a un adjunto.
    - **--CurrentFieldValueSearch--**: Se utiliza para buscar en el campo actual. 
    - **--CurrentFieldMailTo--**: Añade el enlace mailto a los datos del campo actual.
    - **/menuexample/list**: Se utiliza para enlazar el registro o los datos del campo actual con la página de la lista.
    - **/menuexample/add**: Se utiliza para enlazar el registro o los datos del campo actual con la página de adición.
**FormatRecordField**: Permite formatear los datos del registro del campo. 
	  - **human_date**: convierte el registro del campo actual en una fecha legible para los humanos.
	  - **human_time**: convierte el registro del campo actual en hora legible para los humanos.
	  - **human_datetime**: convierte el registro del campo actual en fecha y hora legibles para el ser humano.
	  - **relative_date**: convierte el registro del campo actual en una fecha relativa, por ejemplo, hace unos segundos.
	  - **to_currency('en_US')**: convierte el registro del campo actual en moneda.
	  - **ucwords**: Convierte a mayúsculas la **primera letra**r de cada palabra del **registro de campo** o de los datos actuales.
	  - **ucfirst**: Convierte a mayúsculas la primera letra de cada cadena del registro de campo actual.
	  - **strtolower**: Convierte el registro de campo actual a minúsculas.
	  - **strtoupper**: Convierte el registro de campo actual en mayúsculas.
	  - **str_truncate(50,'...')**: Intercepta la longitud de los datos en el registro de campo actual, hasta el valor especificado.
	  - **aproximate(2)**: Aproxima los datos del registro de campo actual según el valor especificado.
	  - **a_número**: formatea los datos en un registro de campo actual.
	  - **number_to_words('es')**: formatea los datos de un registro de campo actual a palabras.
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
## Subsección 02 - Propiedades de la imagen
* **Tamaño de la imagen**: Se puede establecer el tamaño *pequeño*, *medio* o *grande* de la imagen.
* **Tamaño de la etiqueta de la imagen**: Aquí puedes especificar el ancho y el alto de una imagen.
* **MaxImages**: Puede establecer el número máximo de imágenes que el registro guardará.
### <span style="color:blue">Propiedades del tipo *StarRating</span>
![starrating-field-properties.png](/pages/starrating-field-properties.png)
## Subsección 01 - Pantalla
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
## Subsección 02 - Propiedades de las estrellas
* **NúmeroDeEstrellas**: Puede establecer el número de estrellas que aparecen en el campo de la tasa.
### <span style="color:blue">Propiedades para el tipo *ProgressBar*</span>
![progressbar-field-properties.png](/pages/progressbar-field-properties.png)
## Subsección 01 - Pantalla
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **FieldHeaderIcon**: Permite seleccionar el icono que aparecerá en la cabecera del campo de la columna.
* **Etiqueta de visualización**: Permite establecer el título de la columna del campo.
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
## Subsección 02 - Propiedades de la barra de progreso
**Valor máximo**: Puede establecer el valor máximo de la barra de progreso.
**Clase de la barra de progreso**: Puede establecer una clase personalizada o una clase bootstrap para estilizar la barra de progreso.
### <span style="color:blue">
Propiedades para el tipo *CheckButton*.
</span>
![checkbutton-field-properties.png](/pages/checkbutton-field-properties.png)
## Subsección 01 - Pantalla
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
## Subsección 02 - Propiedades de Comprobación
* **CheckValue**: Si se establece como TRUE, se marca la casilla de verificación.

### <span style="color:blue">Properties for the *RelativeDate* Type</span>
![relativedate-field-properties.png](/pages/relativedate-field-properties.png)
## Subsección 01 - Pantalla
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
* **Enlace de campo**: Se utiliza para vincular un registro de campo concreto a una página.
    - **--CurrentRecordDetails--**: Redirige el registro de un campo a una página de detalles o a una página de visualización.
    - **--CurrentFieldCategory--**: Filtra el registro en función del campo.
    - **--CurrentFieldvalue--**: Se utiliza para vincular los datos de un campo concreto a un archivo o a un adjunto.
    - **--CurrentFieldValueSearch--**: Se utiliza para buscar en el campo actual. 
    - **--CurrentFieldMailTo--**: Añade el enlace mailto a los datos del campo actual.
    - **/menuexample/list**: Se utiliza para enlazar el registro o los datos del campo actual con la página de la lista.
    - **/menuexample/add**: Se utiliza para enlazar el registro o los datos del campo actual con la página de adición.
**FormatRecordField**: Permite formatear los datos del registro del campo. 
	  - **human_date**: convierte el registro del campo actual en una fecha legible para los humanos.
	  - **human_time**: convierte el registro del campo actual en hora legible para los humanos.
	  - **human_datetime**: convierte el registro del campo actual en fecha y hora legibles para el ser humano.
	  - **relative_date**: convierte el registro del campo actual en una fecha relativa, por ejemplo, hace unos segundos.
	  - **to_currency('en_US')**: convierte el registro del campo actual en moneda.
	  - **ucwords**: Convierte a mayúsculas la **primera letra**r de cada palabra del **registro de campo** o de los datos actuales.
	  - **ucfirst**: Convierte a mayúsculas la primera letra de cada cadena del registro de campo actual.
	  - **strtolower**: Convierte el registro de campo actual a minúsculas.
	  - **strtoupper**: Convierte el registro de campo actual en mayúsculas.
	  - **str_truncate(50,'...')**: Intercepta la longitud de los datos en el registro de campo actual, hasta el valor especificado.
	  - **aproximate(2)**: Aproxima los datos del registro de campo actual según el valor especificado.
	  - **a_número**: formatea los datos en un registro de campo actual.
	  - **number_to_words('es')**: formatea los datos de un registro de campo actual a palabras.
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.
## Subsección 02 - Relación de Detalle Maestro
* Página de detalle del registro: Permite establecer las características de una relación entre las tablas maestra y de detalle.
## Subsección 04 - Edición en línea
* **Edición en línea**: Permite especificar si es posible editar los registros de la misma lista.
* **EditFieldControlType**: Permite elegir si la edición inline se basará en lo configurado en la página de Edición o a través de un formato de datos específico.
* **UsePopOverDisplay**: Le permite activar o desactivar la pantalla emergente para la edición en línea.
* **Colocación**: La opción le permite especificar la posición de la pantalla emergente en una edición en línea.
* **Modo de activación**: Puede especificar el método por el que se activa la edición en línea.
* **MostrarBotones**: Permite especificar la posición de los botones que permiten la edición inline.
### <span style="color:blue">Propiedades del tipo *Personalizado</span>
![custom-field-properties.png](/pages/custom-field-properties.png)
## Subsección 01 - Pantalla
* **Sortable**: Si se establece como TRUE, se añadirá un control a la vista de la página que permitirá ordenar la columna por este campo.
* **CustomCode**: Puede insertar su propio código personalizado.
* **FormatRecordField**: Permite formatear los datos del registro del campo. 
	  - **fecha_humana**: convierte el registro del campo actual en una fecha legible para los humanos.
	  - **human_time**: convierte el registro del campo actual en hora legible para los humanos.
	  - **human_datetime**: convierte el registro del campo actual en fecha y hora legibles para el ser humano.
	  - **relative_date**: convierte el registro del campo actual en una fecha relativa, por ejemplo, hace unos segundos.
	  - **to_currency('en_US')**: convierte el registro del campo actual en moneda.
	  - **ucwords**: Convierte a mayúsculas la **primera letra**r de cada palabra del **registro de campo** o de los datos actuales.
	  - **ucfirst**: Convierte a mayúsculas la primera letra de cada cadena del registro de campo actual.
	  - **strtolower**: Convierte el registro de campo actual a minúsculas.
	  - **strtoupper**: Convierte el registro de campo actual en mayúsculas.
	  - **str_truncate(50,'...')**: Intercepta la longitud de los datos en el registro de campo actual, hasta el valor especificado.
	  - **aproximate(2)**: Aproxima los datos del registro de campo actual según el valor especificado.
	  - **a_número**: formatea los datos en un registro de campo actual.
	  - **number_to_words('es')**: formatea los datos de un registro de campo actual a palabras.
* **FieldFooterExpressión**: A través de esta propiedad podemos definir una expresión que se muestra al final de cada página y al pie del campo seleccionado. Puede seleccionar una expresión de ejemplo de la lista desplegable o crear la suya propia.
* **Ancho de columna**: Permite establecer el ancho de la columna del campo.
* **Etiqueta de visualización**: Le permite establecer el título de la columna de campo.