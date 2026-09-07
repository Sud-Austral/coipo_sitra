# Lo que se construyo

## Aviso previo: este repositorio casi no tiene evidencia

Corresponde decirlo antes que nada, porque es el hallazgo principal. La
extraccion registro seis archivos y ninguno es codigo fuente: no hay
manifiestos de dependencias, no hay tecnologias declaradas, no hay variables de
entorno, no hay endpoints y no hay tablas. El README no aporta descripcion
alguna [README.md].

Por lo tanto este documento se escribe casi entero en [PENDIENTE]. No es un
descuido de redaccion: es el resultado. Dice que el analizador no ve nada de
este repositorio, y eso tambien es informacion util para quien tenga que
decidir si el proyecto esta documentado o no.

## Que hace el sistema

[INFERIDO] Lo que hay es un entregable listo para publicar: una pagina y sus
archivos de acompanamiento agrupados en una carpeta de publicacion
[INSUMO/SITRA_publicar/index.html], [INSUMO/SITRA_publicar/LEEME.txt],
[INSUMO/SITRA_publicar/robots.txt], [INSUMO/SITRA_publicar/_headers]. No hay
proceso que transforme nada: en la evidencia no aparece ningun script, ninguna
tarea de construccion ni ningun flujo de trabajo automatizado.

[PENDIENTE] Que capacidades ofrece esa pagina a quien la abre. Sin el contenido
del archivo no se puede nombrar ni un verbo ni una entidad, y nombrarlos a
partir de la sigla del repositorio seria inventar.

[PENDIENTE] Para que sirve cada uno de los tres archivos que acompanan a la
pagina. Sus nombres sugieren funciones, pero un nombre de archivo no es una
funcionalidad y la evidencia no trae su contenido.

## Roles: quien ve que

[PENDIENTE] No hay ningun control de acceso identificable. No se detectaron
guards, decoradores de autorizacion, middleware ni variables de entorno con
credenciales. Con la evidencia disponible no se puede afirmar siquiera que la
distincion entre roles exista en este entregable.

## De donde salen los datos

[PENDIENTE] La fuente. La evidencia no muestra conexiones externas, APIs
consumidas, migraciones ni archivos semilla.

[PENDIENTE] Quien es dueno de lo que se publica y quien autoriza publicarlo.

## Que no hace

Las siguientes ausencias son afirmables porque el extractor busco esas
categorias de forma exhaustiva y volvio vacio; aun asi van marcadas.

[INFERIDO] No expone ningun endpoint: la lista de rutas detectadas esta vacia
en la evidencia.

[INFERIDO] No usa base de datos: la lista de tablas detectadas esta vacia.

[INFERIDO] No declara dependencias de terceros ni de Python ni de Node: las
listas de manifiestos y de dependencias estan vacias.

[INFERIDO] No lee configuracion del entorno: la lista de variables de entorno
esta vacia.

## Iteraciones

[PENDIENTE] No hay CHANGELOG, ni migraciones numeradas, ni flujos de trabajo en
la evidencia. La unica marca de version que consta es la rama por omision del
repositorio en sus metadatos, que no dice nada sobre la evolucion del producto.

## Lo primero que habria que preguntar

Antes de cualquier otra cosa: que es lo que esta publicado en
[INSUMO/SITRA_publicar/index.html] y a que area pertenece. Todo lo demas de
este documento depende de esa respuesta.
