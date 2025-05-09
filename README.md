
---

# 📰 Blog con Autenticación – React + FastAPI + MySQL + AWS

Este proyecto es una aplicación web completa de tipo blog que permite a los usuarios registrarse, iniciar sesión y gestionar publicaciones de forma segura. Los usuarios autenticados pueden crear, editar y eliminar sus propios artículos, así como comentar en publicaciones de otros usuarios.

El proyecto está construido con una arquitectura moderna full stack que integra:

* 🧠 **Backend**: FastAPI (Python), que expone una API REST con autenticación segura mediante JWT.
* 🎨 **Frontend**: React + Vite, que ofrece una interfaz rápida y moderna para interactuar con el usuario.
* 🗄️ **Base de Datos**: MySQL, alojada en AWS RDS, para almacenar usuarios, artículos y comentarios.
* ☁️ **Infraestructura Cloud**: Despliegue del backend en AWS EC2, y conexión segura entre servicios.

## ✨ Funcionalidades

* Registro e inicio de sesión de usuarios con autenticación basada en JWT.
* Creación, edición y eliminación de artículos por el autor.
* Publicación de comentarios en artículos de otros usuarios.
* Protección de rutas privadas mediante validación del token JWT.
* Interfaz web SPA desarrollada con React.
* Backend RESTful con validación de datos usando Pydantic y SQLAlchemy.

## 🔧 Tecnologías utilizadas

| Capa           | Herramientas                     |
| -------------- | -------------------------------- |
| Frontend       | React, Vite, React Router, Axios |
| Backend        | FastAPI, Python, SQLAlchemy, JWT |
| Base de datos  | MySQL (AWS RDS)                  |
| DevOps / Cloud | AWS EC2, AWS RDS, AWS Cloud9     |

