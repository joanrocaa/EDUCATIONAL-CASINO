Personal portfolio version of a collaborative university project.

# Educational Casino Web Platform

A collaborative full-stack web application developed as part of a software engineering project.
The platform simulates an online casino with multiple games, user authentication, statistics tracking and multiplayer option.

---

## Features

* User authentication and session management
* Multiple casino games (singleplayer and multiplayer)
* Real-time updates using WebSocket communication
* Persistent user balance and statistics
* Modular backend architecture using Flask Blueprints

---

## Architecture Overview

The application follows a client-server architecture:

* **Frontend (UI)** renders HTML templates and handles user interaction
* **Backend API** processes game logic, validates actions and updates user data
* **Database models** store users, bets and statistics
* **SocketIO layer** broadcasts real-time updates for multiplayer interactions

Typical flow:

User → Browser → Flask route → Backend logic → Database → Response → UI update

---

## Tech Stack

* Python
* Flask
* Flask-Login
* Flask-SocketIO
* SQLAlchemy
* HTML / CSS / JavaScript

---

## Project Structure (simplified)

src/

* server/

  * app.py (application initialization)
  * models.py (database models)
  * endpoints/ (modular route definitions)
  * socketio_handlers.py (real-time event handling)

* templates/ (HTML views)

* static/ (JavaScript and CSS)

---

## My Contribution

Worked as part of a Scrum development team contributing to:

* Backend route implementation and API logic
* GitHub workflow and task tracking
* Integration and testing of game features

---

## Live Demo

The application is deployed and accessible online:

👉 [CASINO LINK](https://logbait.onrender.com)

(Note: the service may take a few seconds to start if inactive.)

---

## Notes

This project was developed collaboratively as a university software engineering assignment using agile methodologies.

### Original Team Repository

The original team repository can be found here:

[Link to original repository](https://github.com/UCM-FDI-DISIA/proyectois1-thatwasepic)

This personal repository contains the same project with an improved README and documentation for portfolio purposes.



# Plataforma Web de Casino Educativo

Aplicación web full-stack desarrollada en equipo como parte de un proyecto de ingeniería del software.
La plataforma simula un entorno de casino online con múltiples juegos, autenticación de usuarios, seguimiento de estadísticas y funcionalidades multijugador en tiempo real.

---

## Funcionalidades

* Autenticación de usuarios y gestión de sesiones
* Múltiples juegos de casino (individual y multijugador)
* Actualizaciones en tiempo real mediante WebSockets
* Persistencia de saldo y estadísticas de usuario
* Arquitectura backend modular usando Flask Blueprints

---

## Arquitectura

La aplicación sigue una arquitectura cliente-servidor:

* **Frontend (UI)** renderiza las páginas y gestiona la interacción del usuario
* **API Backend** procesa la lógica de los juegos, valida acciones y actualiza datos
* **Modelos de base de datos** almacenan usuarios, apuestas y estadísticas
* **SocketIO** permite actualizaciones en tiempo real para el modo multijugador

Flujo típico:

Usuario → Navegador → Ruta Flask → Lógica backend → Base de datos → Respuesta → Actualización UI

---

## Tecnologías

* Python
* Flask
* Flask-Login
* Flask-SocketIO
* SQLAlchemy
* HTML / CSS / JavaScript

---

## Estructura del proyecto (simplificada)

src/

* server/

  * app.py (inicialización)
  * models.py (modelos)
  * endpoints/ (rutas modulares)
  * socketio_handlers.py (eventos realtime)

* templates/ (vistas HTML)

* static/ (JS y CSS)

---

## Mi contribución

Trabajo dentro de un equipo Scrum participando en:

* Implementación de rutas backend y lógica API
* Gestión del flujo de trabajo con GitHub
* Integración y pruebas de funcionalidades

---

## Demo online

La aplicación está desplegada y accesible aquí:

[👉 LINK CASINO](https://logbait.onrender.com/register)

(Nota: el servicio puede tardar unos segundos en arrancar si está inactivo.)

---

## Nota

Proyecto desarrollado de forma colaborativa como práctica universitaria utilizando metodologías ágiles.

### Repositorio original del equipo

El repositorio original del equipo se encuentra aquí:

[Enlace al repositorio original](https://github.com/UCM-FDI-DISIA/proyectois1-thatwasepic)
