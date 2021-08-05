# DEPLOY ASP NET CORE ON HEROKU
Pasos para hacer deploy de una aplicación hecha en .Net Core en Heroku

## Requerimientos
- .Net Core
- GIT

## Escribir los siguientes comandos en el CLI:
- heroku login
- heroku create {AppName}
- heroku buildpacks:set jincod/dotnetcore
- git push heroku {rama}

## Nota: 
- Para ejecutar los comandos anteriores debe estar ubicado dentro del directorio de su App.
