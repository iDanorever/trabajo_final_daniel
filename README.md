# 🚀 Google Stitch - API de Viajes

API REST desarrollada con Node.js y Express para gestionar información de viajes y dashboards. Este proyecto fue desarrollado como parte del curso de Desarrollo de Software en SENATI.

---

## 🛠️ Tecnologías utilizadas

- **Node.js** + **Express** → Backend
- **Datos mock** → Sin base de datos (estático)

---

## ⚙️ Cómo ejecutar el proyecto

### 1. Clonar el repositorio
```bash
git clone https://github.com/iDanorever/viajes-dashboard.git
cd viajes-dashboard

## 2. Instalar dependencias
```
npm install
```

## 3. Iniciar el servidor
```
node server.js
```
El servidor se ejecutará en: http://localhost:3000

📋 Endpoints disponibles
|Método	|Endpoint	|Descripción
|GET	|/api/viajes	|Obtiene lista de viajes
|GET	|/api/dashboard	|Obtiene datos del dashboard
