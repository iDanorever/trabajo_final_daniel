# 🎯 SENATI - Bolsa de Trabajo y Seguimiento PEA

Aplicación web desarrollada para el curso de Desarrollo de Software en SENATI. Permite gestionar la bolsa de trabajo, registrar empresas, hacer seguimiento del Plan Específico de Aprendizaje (PEA) y administrar el perfil del aprendiz.

---

## 🚀 Tecnologías utilizadas

| Capa | Tecnología | Propósito |
|------|------------|-----------|
| **Frontend** | Next.js, shadcn/ui, Tailwind CSS | Interfaz de usuario moderna y responsiva |
| **Backend** | Node.js, Express | API REST para manejar los datos |
| **Base de Datos** | MySQL (XAMPP) | Almacenamiento de información |

---

## 📁 Estructura del Proyecto

bolsa-trabajo-senati/
├── backend/ # API con Node.js + Express
│ ├── api/
│ │ ├── controllers/ # Lógica de negocio
│ │ └── routes/ # Definición de endpoints
│ ├── index.js # Servidor principal
│ └── package.json
├── frontend/ # Aplicación con Next.js
│ ├── app/ # Páginas (App Router)
│ ├── components/ # Componentes reutilizables
│ ├── lib/ # Utilidades y conexión con API
│ └── package.json
└── README.md


---

## ⚙️ Cómo ejecutar el proyecto

### 1. Clonar el repositorio
```bash
git clone https://github.com/iDanorever/bolsa-trabajo-senati.git
cd bolsa-trabajo-senati
---
cd backend
npm install
npm run dev
