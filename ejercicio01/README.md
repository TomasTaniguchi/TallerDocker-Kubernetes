## Ejercicio N°1

- Dentro de la carpeta **app**.
- Construir la imagen del Dockerfile con _docker build -t app ._.
- Levantar el contenedor con _docker run -d -p <puerto>:80 app_.

## Ejercicio N°1 Con corrección

- _docker run --name ejercicio01 -p 8002:80 -v <Ruta de donde se encuntra mi app>:/usr/share/nginx/html:ro -d nginx_
- Con **-v** en el comando anterior se se crea un volumen donde paso mi app a la ruta _:/usr/share/nginx/html_ del contenedor.
- Ademas le mapeo un puerto con **-p**.
