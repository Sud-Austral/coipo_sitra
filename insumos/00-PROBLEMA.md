# Problema que se deduce del codigo

Advertencia de metodo: este documento se escribe hacia atras, desde lo que hay
construido hacia lo que probablemente estaba roto. La cadena de inferencia es
debil por definicion y aca es mas debil que en la mayoria de los repositorios,
porque la evidencia extraida son seis archivos y ninguno de ellos es codigo.

## Que se puede afirmar con cita

El repositorio contiene un unico entregable: una carpeta de publicacion con una
pagina y tres archivos de apoyo [INSUMO/SITRA_publicar/index.html],
[INSUMO/SITRA_publicar/LEEME.txt], [INSUMO/SITRA_publicar/robots.txt],
[INSUMO/SITRA_publicar/_headers]. El README del repositorio no describe nada:
su unica linea es el nombre del propio repositorio [README.md].

[INFERIDO] Lo entregado es material para publicar tal cual, no un programa que
se ejecute: en la evidencia no hay ningun manifiesto de dependencias, ninguna
tecnologia declarada, ninguna variable de entorno y ningun endpoint. El unico
archivo de peso es la pagina [INSUMO/SITRA_publicar/index.html], de unos 2,8 MB
segun el tamano registrado en la evidencia, y no la acompana ningun archivo de
estilos, de script ni de imagenes dentro de la misma carpeta.

[INFERIDO] Como la pagina no tiene archivos hermanos de los que tirar, lo que
muestra viaja adentro del mismo archivo [INSUMO/SITRA_publicar/index.html]. Eso
es compatible con un entregable que se copia a un servidor y se abre, sin
proceso de construccion.

## Que problema habria detras

[INFERIDO] El sistema entrega una pagina lista para publicar, luego
probablemente habia un problema de publicacion: algo que existia y que no
estaba disponible en la web. Esta es la inferencia mas larga de todo el
documento y no tiene mas respaldo que la existencia de la carpeta
[INSUMO/SITRA_publicar/index.html].

[PENDIENTE] Que contiene esa pagina, sobre que trata y a que proceso de negocio
corresponde la sigla del repositorio. La evidencia no incluye el contenido de
los archivos y el README no lo dice [README.md].

[PENDIENTE] Como se resolvia antes. No hay importadores de planilla, ni
endpoints de carga, ni scripts de transformacion en la evidencia, asi que no
hay ni siquiera un indicio del que colgar una hipotesis.

## Quien sufre el problema

[PENDIENTE] No hay guards, decoradores, middleware de autorizacion ni tabla de
permisos en la evidencia: la extraccion no encontro ningun archivo de codigo.
No se puede nombrar ni un solo rol.

[PENDIENTE] Cuantas personas son. Siempre es pendiente, y aca ni siquiera hay
un indicio que discutir.

## Volumen

[INFERIDO] El unico indicio de orden de magnitud es el tamano del archivo
publicado [INSUMO/SITRA_publicar/index.html]: 2,8 MB de HTML es mucho para una
pagina escrita a mano y es compatible con contenido generado o incrustado. No
prueba cuantos registros hay.

[PENDIENTE] La cifra: cuantos registros, cuantas consultas, cuantos usuarios.

## Que pasa si no se hace nada

[PENDIENTE] El codigo no lo responde y no se deduce de que el repositorio
exista.

## Quien decide que esta terminado

[PENDIENTE] No hay criterio de aceptacion en la evidencia.

## Marco normativo

[VERIFICAR] Si la pagina publicada contiene datos de personas, su publicacion
abierta tiene implicancias que ni el codigo ni este documento pueden resolver.
El repositorio figura como publico en los metadatos de la evidencia, y el
contenido de [INSUMO/SITRA_publicar/index.html] no fue extraido, asi que la
pregunta queda abierta.
