<p align="center">
  🌐 <a href="#-english-version">Read in English</a> | 🇪🇸 <a href="#-versión-en-español">Leer en Español</a>
</p>

---

<h2 id="-english-version">☁️ Self-Hosted Private Cloud & Local AI Infrastructure</h2>

![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale_VPN-242424?style=for-the-badge&logo=tailscale&logoColor=white)
![Llama](https://img.shields.io/badge/Local_AI-Llama_3.2-0467DF?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

Design and orchestration of a self-hosted infrastructure ecosystem (HomeLab) running on an **Ubuntu Server** headless environment. This project focuses on microservices orchestration, high availability, data privacy, and secure remote access.

### 🚀 Architecture & Core Stack
* **OS & Orchestration:** Ubuntu Server LTS + Docker Compose for declarative infrastructure (IaC).
* **Private Cloud Storage:** Deployment of a self-hosted "Google Photos" alternative (microservices architecture with PostgreSQL and Redis) for secure, on-premise media backup.
* **Local AI Stack:** Ollama (running **Llama 3.2 1B**) + Open WebUI for a fully private, ChatGPT-like interface.
* **Networking (Zero-Trust):** Tailscale VPN Mesh implementation to securely access services remotely without exposing router ports or public IPs.
* **Resilience:** Persistent volume mapping, `restart: always` policies, and BIOS AC Power Loss recovery configurations.

### 🧠 Highlight: 100% Private Local Artificial Intelligence
One of the main challenges of this project was deploying a Large Language Model (LLM) entirely on local hardware, ensuring **Zero Data Leakage**. All queries and processing are kept on-premise, isolated from the public internet, making it a viable architecture for handling sensitive corporate data.

*Note: The `docker-compose.yml`, `.gitignore`, and environment configuration templates will be uploaded in the upcoming commits.*

<br>

---

<h2 id="-versión-en-español">☁️ Nube Privada Autohospedada & Infraestructura de IA Local</h2>

![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale_VPN-242424?style=for-the-badge&logo=tailscale&logoColor=white)
![Llama](https://img.shields.io/badge/Local_AI-Llama_3.2-0467DF?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

Diseño y orquestación de un ecosistema de infraestructura autohospedada (HomeLab) ejecutándose en un entorno **Ubuntu Server** *headless*. Este proyecto se centra en la orquestación de microservicios, alta disponibilidad, privacidad de los datos y acceso remoto seguro.

### 🚀 Arquitectura y Stack Tecnológico
* **OS y Orquestación:** Ubuntu Server LTS + Docker Compose para infraestructura declarativa (IaC).
* **Almacenamiento en Nube Privada:** Despliegue de una alternativa autohospedada a "Google Photos" (arquitectura de microservicios con PostgreSQL y Redis) para el respaldo seguro de medios *on-premise*.
* **Stack de IA Local:** Ollama (ejecutando **Llama 3.2 1B**) + Open WebUI para una interfaz tipo ChatGPT totalmente privada.
* **Redes (Zero-Trust):** Implementación de Tailscale VPN Mesh para acceder de forma segura a los servicios de forma remota sin exponer puertos del router ni IPs públicas.
* **Resiliencia:** Mapeo de volúmenes persistentes, políticas `restart: always` y configuraciones de recuperación BIOS ante cortes de energía (AC Power Loss).

### 🧠 Destacado: Inteligencia Artificial Local 100% Privada
Uno de los principales retos de este proyecto fue desplegar un Modelo de Lenguaje Grande (LLM) íntegramente en hardware local, garantizando **Cero Fuga de Datos (Zero Data Leakage)**. Todas las consultas y el procesamiento se mantienen *on-premise* y aislados del internet público, convirtiéndola en una arquitectura viable para el manejo de datos corporativos sensibles.

*Nota: El archivo `docker-compose.yml`, el `.gitignore` y las plantillas de configuración de entorno se subirán en los próximos commits.*
