# Tabla de contenidos
  - [Image Server Go](#image-server-go)
  - [Autor](#autor)
  - [Descripción](#descripción)
  - [Capturas de Pantalla](#capturas-de-pantalla)
  - [Tecnologías Utilizadas](#tecnologías-utilizadas)
  - [Cómo Utilizar](#cómo-utilizar)

# Image Server Go

Image Server Go es una aplicación sencilla diseñada para servir una colección de imágenes de manera aleatoria en un entorno web.

## Autor

Este proyecto fue desarrollado por Pablo Bernal and Juan Daniel Cardona.

## Descripción

Concebido para ser flexible y fácil de desplegar, este servidor de imágenes es ideal tanto para entornos de desarrollo como para producción. La aplicación está planeada para despliegues locales, en máquinas virtuales Debian 12 (Grub) configuradas en modos de red puente y NAT, y mediante contenedores Docker.

## Capturas de Pantalla

### Vista Desktop

![image](https://github.com/9pasb6/pixel_icon_app/assets/100176897/dd98a54d-2457-429f-b514-5aefed17d604)


### Vista Mobile

![c74b4856-9d06-4775-8e66-bba688c25406](https://github.com/9pasb6/pixel_icon_app/assets/100176897/f7e3fb6f-cb8e-49cb-b515-1ae0746c9bb6)

### Vista Docker
![image](https://github.com/9pasb6/pixel_icon_app/assets/100176897/2197e5a8-700c-4218-9f2f-03e1fa197df0)


## Tecnologías Utilizadas

- **Go**: Lenguaje de programación utilizado para implementar la lógica del servidor de imágenes.
- **HTML y CSS**: Utilizados para crear la interfaz de usuario que muestra las imágenes.
- **Docker**: Para contenerizar la aplicación, asegurando la portabilidad y la facilidad de despliegue.
- **Debian 12 (Grub)**: Para la creación de entornos virtuales consistentes y aislados en modo de red puente y NAT.

## Cómo Utilizar

Para correr la aplicación en tu entorno local, sigue estos pasos:

```sh
git clone https://github.com/9pasb6/pixel_icon_app.git
cd pixel_icon_app
docker-compose up -d
