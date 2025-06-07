# 📦 Request Header Parser Microservice

Este proyecto forma parte del curso **Back End Development and APIs** de [FreeCodeCamp](https://www.freecodecamp.org/).

## 🧾 Descripción

El objetivo es construir un microservicio que devuelva información sobre el cliente a partir de las cabeceras HTTP de la solicitud. Este proyecto forma parte de la serie de microservicios del programa y pone en práctica el trabajo con Express y el acceso a información del cliente en las cabeceras de una petición.

## 📥 Uso de la API

La API está disponible en la siguiente ruta:

GET /api/whoami


## 📤 Respuesta esperada

```json
{
  "ipaddress": "123:456:789",
  "language": "en-US,en;q=0.5",
  "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
```

# Campos devueltos

ipaddress: Dirección IP del cliente que hizo la solicitud.

language: Idiomas preferidos del cliente, extraídos de la cabecera Accept-Language.

software: Información del sistema operativo y navegador, obtenida de la cabecera User-Agent.

## 🚀 Tecnologías utilizadas

Node.js
Express.js

## 📚 Requisitos del reto en FreeCodeCamp
El proyecto debe exponer un endpoint /api/whoami.

El endpoint debe devolver un objeto JSON con las claves ipaddress, language y software.
