#Cliente en vanilla JavaScript

Este proyecto consume un servicio Rest que puedes encontrar en [perreraService](https://dithub.com/ipartek/PerreraWebService)

![screenshot](screenshot.pgn?raw=true)

##Tecnología
En este proyecto usamos la siguiente tecnologia

- HTML
- CSS
- JavaScript Vanilla sin FrameWork
- FrameWork de Frontend [Materializecss](https://materializecss.com)


## Configuracion

La URL donde escucha el proyecto se puede cambiar en **js/main.js**, cambiando la siguiente linea:
const endpoint='http://localhost:8080/perreraWS/service/perro?orderBy=asc&campo=id'

Tambien tienes disponible un fichero con datos JSON por si no quieres instalas el proyecto **perreraWebService** en [api/perros.json](https://github.com/ipartek/PerreraVanilaJSClient/tree/master/api)

**Atencion** con CORS, puede que tenfas que utilizar un plugin en tu navegador.
Si usamos firefox, [el siguiente plugin]()

##ejecucion

Es un proyecto web clasico por lo cual podemos ejecutarlo en cualquier servicor web o browser, sin ningun tipo de configuracion extra.
recomendable usar VSCode con el plugin de LiveServer