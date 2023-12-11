# Guía para App Builder.

#### Para [LINKAR] una tabla con cabeceras y líneas:
*Suponiendo que ya hemos creado el window y las dos tablas.*  

Crearemos un nuevo [record] (link de tipo record) entre la tabla de cabeceras y líneas.
Para ello: **Click derecho en cualquier tabla > Smart Links > Add...**  
![foto](/img/record_smart_links.png)

Luego, en la tabla *de las líneas*, editaremos master, y en la lupa, añadimos una nueva tabla externa,
de esta forma:
![foto](/img/add_external_table.png)  

#### Para [MODIFICAR] el browser de una tabla a la que hemos añadido un campo
Lo modificaremos para que sea FreeForm Query.  
Primero tenemos que editar el master, y seleccionar el browser. En la segunda lupa, nos dirigiremos a **Query**,
crearemos la freeform query.
![foto](/img/crear_freeform_query.png)  

Luego, al editar el browser, en el *lápiz*, podremos ver los campos como si fuera código y añadir uno nuevo (**importante utilizar mismo formato que en la BBDD**).  
Se encuentra en [DISPLAY]
![foto](/img/freeform_fields.png)  


### Creación cosas básicas:

**Es necesario un archivo [smartv8.cst] y añadirlo:**
![foto](/img/menu_use_custom.png)  


#### Crear un Browser:
*->* Tener en cuenta: Las querys y los campos, no dar todo siguiente.
#### Crear un Viewer:
*->* Nada importante a tener en cuenta. 
#### Crear un Panel:
*->* **Tiene que ser el [p-updsav.r]**
![foto](/img/crear_panel.png)  


### 🚨 BUGS 🪳

*->* Si se buguean los campos de un browser al poner un campo o modificarlo en la tabla real, y es un freeform query, podemos borrar el formato en su [DISPLAY]:
![foto](/img/bug_formato.png)  


