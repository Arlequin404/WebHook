## Webhook Project with Sinatra and Docker
Description (English)
This project is a simple webhook server built using Sinatra (a lightweight Ruby framework) and containerized with Docker. It listens for POST requests on a specific endpoint and responds with a JSON message.

## Descripción (Español)
Este proyecto es un servidor webhook simple construido con Sinatra (un micro-framework de Ruby) y contenerizado con Docker. Escucha solicitudes POST en un endpoint específico y responde con un mensaje en formato JSON.

**Technologies / Tecnologías**
Ruby: 3.2.6
Sinatra: 4.1.1
Puma: 6.5.0
Docker
**Requirements / Requisitos**
Git (to clone the project)
Docker (to run the project in a container)
Ruby (optional for local execution)
**Installation and Execution / Instalación y Ejecución**
**1. Clone the Project / Clonar el Proyecto**
```bash
git clone https://github.com/username/webhook-sinatra.git
cd webhook-sinatra
```
**2. Run Locally / Ejecutar Localmente**
Install Dependencies / Instalar Dependencias
```bash
bundle install
```
Start the Server / Iniciar el Servidor
```bash
ruby app.rb
```
Access the application at: http://127.0.0.1:4567

**3. Dockerize the Project / Dockerizar el Proyecto**
Build the Docker Image / Construir la Imagen de Docker
```bash
docker build -t webhook-sinatra .
```
Run the Docker Container / Ejecutar el Contenedor de Docker
```bash
docker run -p 4567:4567 webhook-sinatra
```
Access the application at: http://127.0.0.1:4567

Docker Hub Link / Enlace de Docker Hub
Link to Docker Hub
