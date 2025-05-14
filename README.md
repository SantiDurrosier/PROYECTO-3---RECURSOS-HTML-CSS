# Configuración del VSC con Live Sass Compiler

1. Instalar la extensión Live Sass Compiler

2. Tener una estructura básica de "assets", donde dentro tenga una carpeta "scss".

3. En "Administrar", voy a "configuración"

![alt text](/README/image.png)

En la pantalla que me sale, escribo "json". Me saldrá un listado del que debo elegir la siguiente opción
![alt text](/README/image-1.png)

4. En el json vamos a incluir el siguiente código:

```bash

    "liveSassCompile.settings.formats":[    
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "~../css"
        },
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "~../css"
        }
    ],

```

