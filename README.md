# 🏠 Beelink Home Server Setup

Configuración inicial de un laboratorio doméstico (Home Lab) usando un Mini PC Beelink. El objetivo es crear un servidor de contenedores robusto para desplegar microservicios.

## ⚙️ Hardware
* **Modelo:** Beelink Mini PC
* **CPU:** Ryzen 7
* **RAM:** 20GB+

## 🚀 Instalación y Configuración

### 1. Sistema Operativo
* Instalación limpia de **Ubuntu Server**.
* Configuración de acceso SSH para administración remota.

### 2. Motor de Contenedores (Docker)
Instalación del motor Docker para la orquestación de servicios:
```bash
# Comprobar instalación
docker --version