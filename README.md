# Instalación Docker

## Introducción

![](https://github.com/MelissaRodriguezHernandez/Docker/blob/main/img/logo.png)

Docker es una herramienta que permite empaquetar una
aplicación y sus dependencias en un contenedor muy ligero. Es
como si tomaras una aplicación completa con absolutamente
todo lo que necesita para funcionar para poder transportarla sin
problema a cualquier otro servidor con Docker instalado, ya sea
para seguir desarrollándose o para hacer deploy.

## Instalación en Windows

Primero descargamos el archivo .exe de la página web oficial y lo ejecutamos

[Link de descarga](https://docs.docker.com/desktop/windows/install/)

![](https://github.com/MelissaRodriguezHernandez/Docker/blob/main/img/ejecutar.png)
![](https://github.com/MelissaRodriguezHernandez/Docker/blob/main/img/terminar.png)

Al abrir por primera vez Docker tendremos que introducir nuestras credenciales como usuario.
Si todo inicia correctamente podremos acceder a un pequeño tutorial que nos proporcionara la plataforma.

![](https://github.com/MelissaRodriguezHernandez/Docker/blob/main/img/tutorial.png)

Finalmente para corraborar que todo este funcionando correctamente  podemos ejecutar el contenedor 'Hello-World'.

```
docker run hello-world
```

![](https://github.com/MelissaRodriguezHernandez/Docker/blob/main/img/hello.png)
