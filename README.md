# 📦 LogiCorp - Inventory & Sales Report System

Sistema web desarrollado en Laravel para la gestión de inventario de productos y generación de reportes mensuales de ventas en PDF.

---

## 🚀 Tecnologías utilizadas

- PHP 8.2+
- Laravel 12
- MySQL
- Blade Templates
- jQuery (AJAX)
- Bootstrap 5
- DomPDF (barryvdh/laravel-dompdf)

---

## 📌 Funcionalidades

### 📦 Inventario de productos
- CRUD completo de productos
- Relación con categorías
- Validaciones en backend y frontend
- Interfaz dinámica con AJAX (sin recargar página)

### 📊 Reporte de ventas
- Generación de reporte mensual en PDF
- Consolidación de ventas por producto
- Total de unidades vendidas
- Ingresos totales
- Diseño tipo reporte ejecutivo

---

## ⚙️ Instalación del proyecto

### 1. Clonar repositorio
```bash
git clone https://github.com/DavidSib24/LogiCorp.git
cd inventory-system
composer install
npm install
npm run dev
cp .env.example .env

--Verificar el .env
DB_DATABASE=inventory-system
DB_USERNAME=root
DB_PASSWORD=

--Generar key
php artisan key:generate

--Generar migration y seeders
php artisan migrate --seed

--Iniciar server
php artisan serve
