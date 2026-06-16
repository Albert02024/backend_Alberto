# 🚀 API REST con Node.js y Express

<p align="center">
  <img src="./img/proposito-aplicacion.png" alt="Propósito de Aplicación" width="900">
</p>

<p align="center">

![Node.js](https://img.shields.io/badge/Node.js-22.x-green?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Framework-black?logo=express)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

## 📖 Descripción

Este proyecto tiene como objetivo comprender el funcionamiento de un servidor web utilizando **Node.js** y **Express.js**, el framework backend más utilizado en la industria para la construcción de aplicaciones web y APIs REST.

A través de esta aplicación se aprenderá cómo procesar solicitudes HTTP, gestionar rutas y devolver respuestas en formato JSON, sentando las bases para futuros desarrollos que incluyan:

* Bases de datos.
* Autenticación y autorización.
* Arquitecturas RESTful.
* Despliegue en servicios cloud.

---

## 📑 Tabla de Contenidos

* [📖 Descripción](#-descripción)
* [🎯 Objetivos](#-objetivos)
* [🛠️ Tecnologías](#️-tecnologías)
* [📂 Estructura del Proyecto](#-estructura-del-proyecto)
* [⚙️ Instalación](#️-instalación)
* [🚀 Ejecución](#-ejecución)
* [📡 Ejemplo de Respuesta](#-ejemplo-de-respuesta)
* [📚 Conceptos Aprendidos](#-conceptos-aprendidos)
* [🤝 Contribuciones](#-contribuciones)
* [📄 Licencia](#-licencia)

---

## 🎯 Objetivos

* Comprender la arquitectura cliente-servidor.
* Crear un servidor utilizando Express.js.
* Gestionar rutas HTTP.
* Enviar respuestas JSON.
* Organizar proyectos backend siguiendo buenas prácticas.
* Preparar el proyecto para futuras integraciones con bases de datos y sistemas de autenticación.

---

## 🛠️ Tecnologías

| Tecnología | Descripción                                |
| ---------- | ------------------------------------------ |
| Node.js    | Entorno de ejecución para JavaScript       |
| Express.js | Framework para aplicaciones web y APIs     |
| JavaScript | Lenguaje de programación                   |
| JSON       | Formato estándar para intercambio de datos |

---

## 📂 Estructura del Proyecto

```text
proyecto/
│
├── img/
│   └── proposito-aplicacion.png
│
├── node_modules/
│
├── routes/
│   └── index.js
│
├── controllers/
│   └── controller.js
│
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/nombre-repositorio.git
```

### 2. Acceder al proyecto

```bash
cd nombre-repositorio
```

### 3. Instalar dependencias

```bash
npm install
```

---

## 🚀 Ejecución

### Modo normal

```bash
node app.js
```

### Modo desarrollo (Nodemon)

```bash
npm run dev
```

Servidor disponible en:

```text
http://localhost:3000
```

---

## 📡 Ejemplo de Respuesta

### Solicitud

```http
GET /
```

### Respuesta

```json
{
  "message": "Servidor funcionando correctamente"
}
```

---

## 📚 Conceptos Aprendidos

* HTTP y protocolo cliente-servidor.
* Métodos HTTP:

  * GET
  * POST
  * PUT
  * DELETE
* Creación de rutas.
* Middleware.
* Respuestas JSON.
* Organización de proyectos backend.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas.

1. Haz un Fork del proyecto.
2. Crea una rama para tu funcionalidad.

```bash
git checkout -b feature/nueva-funcionalidad
```

3. Realiza tus cambios.
4. Envía un Pull Request.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.

Puedes utilizarlo con fines educativos y de aprendizaje.

---

<p align="center">
  Desarrollado con ❤️ utilizando Node.js y Express.js
</p>
