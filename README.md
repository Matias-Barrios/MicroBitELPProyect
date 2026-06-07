# Curso: Programación de Micro:bit con MicroPython

Este repositorio contiene el **material fuente y los archivos de desarrollo** para el curso introductorio de computación física utilizando la tarjeta programable BBC micro:bit y el lenguaje de programación MicroPython.

> ⚠️ **Nota importante:** Este repositorio aloja exclusivamente el archivo de trabajo reproducible de eXeLearning (`.elpx`). Si estás buscando la versión web interactiva lista para visualizar en el navegador, visitá el repositorio de producción o el enlace a GitHub Pages correspondiente.

---

## 🚀 Acerca del Proyecto

El objetivo de este curso es guiar a estudiantes (especialmente enfocado a nivel de educación secundaria/liceal) desde los conceptos más básicos de la robótica educativa y el pensamiento computacional hasta el despliegue de software real en sistemas embebidos.

### Contenidos clave del curso:
* **Introducción al Hardware:** Qué es la BBC micro:bit, sus sensores integrados y su matriz de LED de 5 por 5.
* **Simulación Interactiva:** Uso y herramientas básicas de la plataforma web Microsoft MakeCode.
* **Desarrollo con MicroPython:** Transición de bloques a código textual, lógica de programación orientada a eventos y control de variables globales.
* **Prácticas Guiadas:** Tutoriales dinámicos y ejemplos de código interactivos paso a paso (como el control de movimiento de píxeles en pantalla).

---

## 🛠️ Estructura del Repositorio

Dado que eXeLearning empaqueta todos los recursos multimedia y estructuras en un único entorno de desarrollo, la arquitectura de este repositorio es simple pero pesada:

```text
├── assets/                       # Recursos locales, imágenes y multimedia del curso
├── microbit-con-python.elpx      # Archivo fuente principal de eXeLearning (Tracked por Git LFS)
└── README.md                     # Este archivo de presentación
```

## 📦 Requisitos para Contribuir o Editar
Debido al tamaño de los recursos multimedia incluidos en el proyecto, el archivo fuente .elpx supera los límites estándar de GitHub. Para trabajar con este repositorio de forma local, es indispensable contar con las siguientes herramientas:

*eXeLearning*: Herramienta de autor de código abierto utilizada para diseñar los contenidos interactivos.

*Git LFS (Large File Storage)*: Extensión de Git necesaria para clonar y trackear el archivo .elpx sin errores de buffer o límites de espacio.

# Instrucciones de clonación:

Si vas a descargar este proyecto en tu entorno local, asegurate de tener Git LFS instalado en tu sistema antes de clonar:

# Instalar Git LFS (en sistemas basados en Debian/Ubuntu)

```sudo apt install git-lfs```

# Clonar el repositorio normalmente

```git clone git@github.com:Matias-Barrios/MicroBitELPProyect.git```

# Asegurar la descarga de los archivos pesados

```git lfs pull```

## 🔄 Flujo de Trabajo (Workflow)
Para mantener la consistencia del proyecto, el flujo de desarrollo se divide en dos etapas:

*Edición*: Se realizan las modificaciones de texto, inserción de iDevices y bloques de código directamente sobre el archivo microbit-con-python.elpx usando eXeLearning y se suben los cambios a este repositorio.

*Publicación*: Una vez finalizados los cambios, se exporta el proyecto desde eXeLearning como Sitio Web (Carpeta autocontenida) y se actualiza el repositorio público de producción para su despliegue automático en la web.