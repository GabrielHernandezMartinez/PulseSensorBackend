
# PulseSensorBackend

Este proyecto es un backend desarrollado en Node.js y Express que permite la gestión y monitoreo de usuarios y niveles de estrés a través de sensores de pulso. Utiliza WebSockets para comunicación en tiempo real y MongoDB para el almacenamiento de datos. El sistema está diseñado para integrarse con aplicaciones que requieren el análisis y seguimiento de datos biométricos, facilitando la investigación y el desarrollo de soluciones para la medición del estrés.

Para más detalles sobre la metodología, resultados y contexto académico, consulta el siguiente documento:

[Ver PDF ECORFAN Journal Niveles de Estrés](docs/ECORFAN%20Journal%20Niveles%20de%20estres.pdf)

---

## Tecnologías utilizadas

- Node.js
- Express.js
- MongoDB (Mongoose)
- WebSockets (ws)
- MySQL (opcional, según dependencias)

## Dependencias principales

- express
- mongoose
- ws
- cors
- body-parser
- dotenv
- mysql

## ¿Cómo ejecutar el proyecto?

1. Clona el repositorio y entra a la carpeta del proyecto.
2. Instala las dependencias:
	```bash
	npm install
	```
3. Configura las variables de entorno en un archivo `.env` (por ejemplo, `MONGODB_URI` y `PORT`).
4. Inicia el servidor:
	```bash
	npm start
	```
5. El backend estará disponible en el puerto configurado (por defecto 3000).
