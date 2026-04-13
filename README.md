# 🛒 Shopping Cart - Arquitectura de Microservicios

## 📌 Descripción

Este proyecto implementa un sistema de carrito de compras con arquitectura
de microservicios usando Node.js, React y PostgreSQL.

## 🏗️ Arquitectura
ecommerce/
├── gateway/     → API Gateway con JWT (puerto 3000)
├── products/     → Microservicio productos (puerto 3001)
├── orders/       → Microservicio pedidos (puerto 3002)
├── frontend/        → React + Vite + Tailwind (puerto 5173)
├── database/        → Scripts SQL
└── docs/            → Evidencias del proyecto
