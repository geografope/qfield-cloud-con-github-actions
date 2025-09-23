<img src="img/banner.png">

✨ En este repositorio 📁 encontrarás una guía detallada de como automatizar 📝📍🗺️ reportes georreferenciados usando las bondades que brinda la plataforma de **GitHub**, en especial 🤖 `GitHub Actions` junto con una plantilla personalizada en `Quarto` asociado a un 🌍📲 formulario implementado en `Qfieldcloud`.

¿Asombroso, verdad? 🤓☝️

Para este video usaremos la siguiente herramientas 👇:

- [**Positron**](https://positron.posit.co/): Interfaz de Desarrollo Integrado (IDE) para ciencia de datos.

- [**Quarto**](https://quarto.org/): Sistema moderno open source para la publicación científica y técnica de documentos dinámicos, sitios webs, libros, etc.

- [**Qfieldcloud**](https://qfield.cloud/): Plataforma que permite alojar, dar seguimiento, sincronizar y fusionar formularios desarrollados en [qfield](https://qfield.org/).

- [**QGIS**](https://www.qgis.org/): Software de Sistema de Información Geográfica libre y de código abierto que permite manipular, editar, analizar y visualizar datos espaciales.

- [**Python**](https://www.python.org/): Lenguaje de programación de alto nivel orientado a objetos y funcional.

- [**GitHub Actions**](https://docs.github.com/es/actions/get-started/understand-github-actions): Plataforma que te permite automatizar flujos de trabajo dentro del marco de ciclo de vida del desarrollo de software.

## ⚫ Consideraciones

### Facturación en QfieldCloud

| Característica                              | Comunidad | Pro                 | Organización              | Nube privada   |
|---------------------------------------------|-----------|---------------------|---------------------------|----------------|
| Proyectos públicos                           | ilimitado | ilimitado           | ilimitado                 | ilimitado      |
| Proyectos privados                           | ilimitado | ilimitado           | ilimitado                 | ilimitado      |
| Colaboración en proyectos públicos           | Sí        | Sí                  | Sí                        | Sí             |
| Colaboración en proyectos privados           | No        | 1 colaborador Pro   | dentro de la organización | a medida       |
| Alojamiento de datos incluido                | 100 MB    | 1 GB                | 1 GB                      | a medida       |
| Versiones de archivos                        | 3         | 10                  | 10                        | a medida       |
| Proyectos basados en archivos                | Sí        | Sí                  | Sí                        | Sí             |
| Soporte de capas PostGIS sin conexión (offline) | No     | Sí                  | Sí                        | Sí             |

Fuente: [Qfieldcloud Pricing, 2025](https://qfield.cloud/pricing/)

### Límite de almacenamiento en GitHub

| Plan | Almacenamiento
|------|----------------
| GitHub (free) | Ilimitado
| GitHub (privado) | 500 MB

Fuente: [GitProtect, 2025](https://gitprotect.io/blog/github-storage-limits/)

### Límite de paso de archivos en GitHub

|Plan	|Tamaño de archivo	|
|-----|-------------------
|GitHub gratis| 2GB|
|GitHub Pro	| 2GB|
|GitHub Team	| 4GB|
|GitHub Enterprise Cloud| 5GB|

Fuente: [GitHub Docs, 2025](https://docs.github.com/es/repositories/working-with-files/managing-large-files/about-git-large-file-storage)

> [!NOTE]
> GitHub permite subir archivos menores a **50MB** sin ningun problema, pero si pasa este tamaño saldrá mensajes de advertencias; sin embargo, si el peso es superior a los **100MB**, este se bloqueara automáticamente recomendado utilizar almacenamiento de archivos de gran tamaño de Git [(Git LFS)](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage).


### Facturación para GitHub Actions

|Plan	|Almacenamiento	|Minutos (por mes)
|-----|---------------|-----------------
|GitHub gratis (repositorio privado)|	500 MB|	2.000
|GitHub Pro|	1 GB	|3.000
|GitHub Gratis| para organizaciones	|500 MB|	2.000
|Equipo de GitHub|	2GB|	3.000
|GitHub Enterprise| Cloud	50 GB|	50.000

Fuente: [GitHub Docs, 2025](https://docs.github.com/en/billing/concepts/product-billing/github-actions#included-storage-and-minutes)


## ⚫ Pasos a realizar

Para este tutorial vamos a seguir los siguientes procesos :

1. Crear un formulario básico en QGIS y subir a QfieldCloud.

2. Desarollar una plantilla base para el reporte en quarto.

3. Implementación de un script en python que permite obtener los datos almacenados en QfieldCloud.

4. Automatizar el renderizado del reporte con GitHub Actions.

Todo el proceso desarrollado esta explicado al detalle en el siguiente video de YouTube 🎥.

[![Watch the video](https://img.youtube.com/vi//0.jpg)](https://www.youtube.com/watch?v=)


¡Enteráte más y aprender conmigo! 🔍💡 Suscríbete, activa las notificaciones 🔔 y únete a la comunidad que ama el software libre de código abierto. 🌟🌍 👇
- <img src='https://raw.githubusercontent.com/geografope/recursos/d7be118ef25f46cb6f748d623012bcc9c8e76db6/youtube.svg' width=20 align='center'>https://www.youtube.com/@geografope

- <img src='https://raw.githubusercontent.com/geografope/recursos/d7be118ef25f46cb6f748d623012bcc9c8e76db6/tiktok.svg' width=15 align='center'>https://www.tiktok.com/@geografope

- <img src='https://raw.githubusercontent.com/geografope/recursos/d7be118ef25f46cb6f748d623012bcc9c8e76db6/linkedin.svg' width=15 align='center'>https://www.linkedin.com/in/antonybarja/

## ⚫ Referencias:

- *Tomasz Lisowski, GitHub Storage Limits, 2025, https://gitprotect.io/blog/github-storage-limits/*

- *Documentación de GitHub, 2025, https://docs.github.com/es*

- *Understand GitHub Actions, 2025, https://docs.github.com/es/actions/get-started/understand-github-actions*

- *Rajdeep Singh, Learn to Use GitHub Actions: a Step-by-Step Guide, 2025, https://www.freecodecamp.org/news/learn-to-use-github-actions-step-by-step-guide/*
