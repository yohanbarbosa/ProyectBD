# 📦 Status Car Audio - Base de Datos

Este proyecto consiste en el diseño e implementación de una base de datos relacional para **Status Car Audio**, un negocio dedicado a la venta de sistemas de sonido, pantallas, luces LED y accesorios electrónicos para vehículos.

---

## 📘 Descripción del Proyecto

La base de datos modela la estructura del negocio, permitiendo registrar:

- Productos y sus categorías jerárquicas.
- Clientes y empleados.
- Ventas y sus respectivos detalles.
- Garantías según el tipo de producto (nacional o importado).

---

## 🧱 Estructura de la Base de Datos

### Tablas principales:

- `category`: Categorías jerarquizadas de productos.
- `product`: Información de productos (nombre, precio, nacional/importado, etc.).
- `customer`: Información de clientes.
- `employee`: Información del personal que atiende ventas.
- `sale`: Encabezado de cada venta realizada.
- `sale_detail`: Detalles de los productos vendidos en cada venta.

---

## 🔒 Restricciones y Reglas de Negocio

- Los productos **nacionales** incluyen garantía, los **importados** no.
- Las relaciones entre tablas están protegidas con claves foráneas (`FOREIGN KEY`).
- Los valores nulos están restringidos en campos clave para asegurar integridad.

---

## 🛠️ Tecnologías Usadas

- PostgreSQL / SQL estándar
- pgAdmin / DBeaver (para gestión visual)
- Git / GitHub (para control de versiones)

---

## 🚀 Cómo usar este proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/status-car-audio-db.git
