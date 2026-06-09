# Proyecto DAW 1 — Frontend

Panel de administración web para taller de reparación de teléfonos. Gestiona reparaciones, repuestos, técnicos, órdenes y facturación.

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> Proyecto académico — Desarrollo de Aplicaciones Web · Universidad de Guayaquil

---

## Módulos

| Módulo | Descripción |
|--------|-------------|
| **Reparaciones** | CRUD de órdenes de reparación (por cédula, técnico, equipo, problema) |
| **Repuestos** | Lista y búsqueda de repuestos con filtros por proveedor y categoría |
| **Técnicos** | Gestión del personal técnico |
| **Facturas** | Generación y aprobación de facturas por orden |
| **Usuarios** | Registro y login con roles |

---

## Stack

| Capa | Tecnología |
|------|-----------|
| Framework | React (Create React App) |
| Routing | React Router |
| HTTP | fetch API via controlador centralizado |

---

## Backend

Consume la API REST de [TallerMoviles_API](https://github.com/Mickaell22/TallerMoviles_API) — Node.js + Express + Prisma.

---

## Correr localmente

```bash
git clone https://github.com/Mickaell22/TallerMoviles_Frontend.git
cd TallerMoviles_Frontend
npm install
npm start
```

Disponible en `http://localhost:3000`
