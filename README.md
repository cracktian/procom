# procom
Plataforma para registro y aprobación de proyectos comunitarios.
La Interfaz debe mostrar información general sobre las líneas de inversión comunitaria y los criterios de evaluación de los proyectos.

Funciones del Usuario Iniciador
1.	Creación de proyecto nuevo ingresando datos en formulario de registro
2.	Carga y Eliminación de documentos asociados al proyecto
3.	Revisión del estado de proyecto en el portafolio
4.	Lectura de comentarios asociados al proyecto
5.	Modificación y Eliminación proyecto del portafolio
Funciones del Usuario Evaluador
1.	Lectura de proyecto desde Portafolio
2.	Descarga de documentos asociados al proyecto
3.	Modificación de estado de proyecto
4.	Creación de comentarios asociados al proyecto
Funciones del Usuario Aprobador
1.	Lectura de proyecto desde Portafolio
2.	Modificación de estado de proyecto
3.	Creación de comentarios asociados al proyecto
Funciones del Sistema
1.	Almacenamiento del formulario de ingreso de los detalles del proyecto incluyendo cargador de documentos con campo título
2.	Generación de portafolio indexado de proyectos incluyendo Responsable, Título, Categoría y Estado del proyecto
3.	Generación de documento PDF con el resumen seccionado del detalle del proyecto y listado de títulos de documentos asociados
Reglas del proceso
1.	Solamente el iniciador puede eliminar o modificar el contenido del proyecto y sus documentos asociados (transparencia)
2.	Evaluador y Aprobador pueden crear, leer, modificar y eliminar sus propios comentarios, el Iniciador solamente puede leer
3.	Evaluador no puede modificar o eliminar comentarios de Aprobador
4.	Aprobador no puede modificar o eliminar comentarios de Evaluador
5.	El Iniciador no puede modificar el presupuesto de un proyecto en estado Evaluado o Aprobado
