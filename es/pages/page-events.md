---
title: Eventos de Páginas
description: Maneje acciones en las Páginas
published: true
date: 2024-10-26T02:47:30.014Z
tags: 
editor: markdown
dateCreated: 2022-06-23T20:53:21.012Z
---

# Eventos de página
**Eventos de página** donde se puede insertar un código que se ejecutará antes y después de la función de acción principal.

![page-events.png](/page-events/page-events.png)

# Cómo utilizarlo
1. Haga clic en **Eventos de página** en la barra de herramientas de RS: aparecerá la ventana de Eventos de página.

![1.png](/page-events/1.png)

2. Haga clic y expanda el árbol de páginas y haga clic en **"Antes... "** o **"Después... "**.

![2.png](/page-events/2.png)

3. Haga clic en el botón **Editar evento de página** para activar la ventana de código.

![3.png](/page-events/3.png)

4. Pon tu código dentro de la función dada.
5. En la parte derecha, hay un fragmento de código incorporado que puedes utilizar con sólo hacer doble clic.

![4.png](/page-events/4.png)
![5.png](/page-events/5.png)

> Nota: Si desea eliminar el código de su evento de página, haga clic en **Borrar evento de página**.
{.is-info}


# Ejemplo
Para nuestro ejemplo vamos a crear un sistema de registro en el que podemos hacer un seguimiento de cada nuevo Todo añadido.

1. Cree una base de datos, nómbrela: **todo-db**
2. Crear la primera tabla, nombrarla: **Todos**
3. Crear 2 campos para la tabla Todos
- **id** *(INT AUTO_INCREMENTO PRIMARIO NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

4. Crear la segunda tabla, nombrarla: **Logs**
5. Crear 4 campos para la tabla Logs
- **id** *(INT AUTO_INCREMENTO PRIMARIO NOT NULL)*
- **dt** *(TIMESTAMP DEFAULT CURRENT_TIMESTAMP)*
- **acción** *(VARCHAR(15) NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

6. En RS Studio, haga clic en **Eventos de página** en la barra de herramientas.
7. Despliegue el árbol **Páginas -> Todos -> Añadir** y haga clic en **Después de añadir**.
8. Haga clic en **Editar evento de página**.
9. Coloca tu código dentro de la función.
10. Utiliza el código de abajo para el lenguaje específico que estés utilizando.
11. Haga clic en **Okay** para guardar.
12. En RS Studio, haga clic en **Publicar** o **Republicar proyecto**.

> Así, cada vez que se añade un nuevo Todo en el módulo Todos, se guarda un registro en el módulo Logs.
{.is-success}


## PHPRad Classic (PHP Laravel + Boostrap Jquery)
```
    private function afterAdd($record){
        //introducir declaración aquí
        
        $modeldata = ['action' => 'Add', 'todo' => $record['todo']];
        DB::table('Logs')->insert($modeldata);
    }
```

## PHPRad Vue (PHP Laravel + Quasar Vue)
```
    private function afterAdd($registro){
        //introducir declaración aquí
        
        $modeldata = ['action' => 'Add', 'todo' => $record['todo']];
        DB::table('Logs')->insert($modeldata);
    }
```

## NodeRad Vue (NodeJS Express + Quasar Vue)
```
async function afterAdd(record, req){
    //introducir declaración aquí
    
    let tableModel = models.Logs; //Logs es el nombre de la tabla
    let modeldata = {
        acción: 'Add',
        todo: record.todo
    }
    
    await tableModel.create(modeldata);
}
```

## PyRad Vue (Python Flask + Quasar Vue)
```
def after_add(record):
    # declaración aquí
    
    new_record = Logs(action="Add", todo=record.todo)
    db.session.add(new_record)
    db.session.commit()
```

## ASPRad Vue (ASP .Net Core + Quasar Vue)
```
private void afterAdd(Todos record){
   //introducir declaración aquí
            
   var modeldata = new Logs(); //Logs es el nombre de la pestaña o del modelo
            
	 modeldata.action = "Add";
   modeldata.todo = record.todo;
   DB.Logs.Add(modeldata);
   DB.SaveChanges();
}
```