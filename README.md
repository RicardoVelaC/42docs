# [WIP] 42docs
Este repositorio contiene notas, comentarios personales y algunos links útiles sobre los proyectos que he realizado en 42 Madrid.

## Modificar el contenido en local
- Clona este repo:

```git clone git@github.com:RicardoVelaC/42docs.git```

- Entra a la carpeta y lanza un `docker-compose up`

- La web estará disponible de forma local desde `http://localhost:4000` 

- Cuando realizes cambios en los archivos `.md` del directorio `/docs` el contenedor los detectará y automáticamente recreará los estáticos para ver el resultado recargando la web.

- Si realizas cambios en la configuración `_config.yml` tendrás que volver a lanzar el comando `docker-compose up --build` con el parámetro `--build` para que vuelva a generar el sitio completo.