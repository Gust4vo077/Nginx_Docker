# Project: Nginx Reverse Proxy with Multiple Backends on Docker

## Overview
This project sets up **Nginx** as a reverse proxy to route traffic to multiple backend services running in Docker containers. It provides load balancing, service discovery, and SSL termination (optional). The architecture is ideal for microservices or applications requiring multiple backend APIs.

## Project Architecture
- **Nginx (Reverse Proxy):** Acts as the entry point and routes traffic based on predefined rules.
- **Backend Services:** Multiple backend applications (e.g., `backend1`, `backend2`, `backend3`), each running in separate Docker containers.
- **Docker Compose:** Manages multi-container deployment.
- **Environment Variables:** Configurable settings for backends and Nginx behavior.

## Key Features
- ✅ **Reverse Proxying** – Routes incoming requests to appropriate backend services.
- ✅ **Load Balancing** – Distributes traffic evenly among multiple backend instances.
- ✅ **SSL Termination** – Secure HTTPS connections using Let's Encrypt (optional).
- ✅ **Scalability** – Easily scale backend services using Docker Compose.
- ✅ **Service Discovery** – Dynamically resolve backend services using Docker networking.
