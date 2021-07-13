# DEPLOY ASP NET CORE ON HEROKU
Pasos para hacer deploy de una aplicación hecha en .Net Core en Heroku

##Requisitos
- .Net Core
- GIT

##Escribri los siguientes comandos en el CLI:
- heroku login
- heroku create {AppName}
- heroku buildpacks:set jincod/dotnetcore
- git push heroku {rama}

##Nota: debe estar ubicado dentro del directorio de su App
