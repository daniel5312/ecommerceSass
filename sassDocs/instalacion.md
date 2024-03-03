## creamos nustra carpeta del proyecto y dentro de ella  intalamos los archivos y lo habrimos en el VSCODE.
##
## creamos nuestro primero el archivo
index.html
# luego creamos nuestra carpeta de Sass "scss" que es nuestro input o salida. y en ella el siguientes archivo
main.scss
## luego creamos nuestra carpeta de css
:/css/main.css/main.css.map
##  luego instalamos unas extenciones que nos van a ayudar a trabajar Sass en nuestro VS CODE.

# extenciones
-Sass
-live Sass compiler
-live server

## luego vamos a los ajustes, configuracion o ssetings del visual studio code y vamos a buscar (Sass) le damos enter y luego buscamos (Ssass fortmat) y buscamos en el. (live Sass> settings: format) le damos en ir al codigo en edit in (settings.json). 

## y lo verificamos y lo editamos de lasiguiente manera:

{
    "workbench.colorTheme": "2077",
    "workbench.iconTheme": "material-icon-theme",
    "editor.linkedEditing": true,
    "liveSassCompile.settings.formats": [
        



        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/css",
            "savePathReplacementPairs": null
        }
    ],
    "liveSassCompile.settings.includeItems": [

        
    ],
    "window.zoomLevel": 0
}

## luego damos en nuestro vscode para poner correr nuestro proyecto

ctrl + shif + P  y escribimos (live Sass:watching Sass) y le danos enter:
y empieza a correr nuestro proecto en la terminal

## luego en nuestro archivo html y lo conectamos al main.css que esta en la carpeta css
## luego vamos a nuestro archivo