# 🛒 Proyecto de Base de Datos para un E-commerce

## 📖 Descripción

Este proyecto consiste en el diseño e implementación de una base de datos avanzada para una plataforma de comercio electrónico (E-commerce). El sistema permite gestionar de forma eficiente productos, categorías, proveedores, clientes, ventas e inventario, incorporando funcionalidades avanzadas como consultas analíticas, funciones definidas por el usuario (UDFs), procedimientos almacenados, triggers, eventos programados y un esquema completo de seguridad.

El objetivo principal es garantizar la integridad, escalabilidad y eficiencia de los datos, proporcionando además herramientas de análisis y automatización para la toma de decisiones empresariales.

---

## 🎯 Objetivos del Proyecto

* Diseñar una base de datos relacional robusta para un sistema E-commerce.
* Implementar restricciones y reglas de negocio que aseguren la calidad de los datos.
* Desarrollar consultas analíticas para la generación de reportes estratégicos.
* Crear funciones reutilizables para encapsular lógica de negocio.
* Implementar procedimientos almacenados para operaciones complejas y transaccionales.
* Automatizar procesos mediante triggers y eventos programados.
* Configurar roles, usuarios y permisos para garantizar la seguridad del sistema.

---

## 🏗️ Modelo de Negocio

La base de datos se estructura alrededor de las siguientes entidades principales:

* **Productos**
* **Categorías**
* **Proveedores**
* **Clientes**
* **Ventas**
* **Detalle de Ventas**

### Relaciones Principales

* Una categoría puede contener múltiples productos.
* Un proveedor puede suministrar múltiples productos.
* Un cliente puede realizar múltiples compras.
* Una venta puede incluir múltiples productos.
* La relación entre ventas y productos se implementa mediante la tabla **Detalle_Ventas**.

---

## 📂 Estructura del Repositorio

```text
Proyecto_BD_Avanzada_[NombreEquipo]
│
├── 01_Esquema_y_Datos.sql
├── 02_Consultas_Avanzadas.sql
├── 03_Funciones.sql
├── 04_Seguridad.sql
├── 05_Triggers.sql
├── 06_Eventos.sql
├── 07_Procedimientos_Almacenados.sql
└── README.md
```

---

## 📋 Contenido de los Scripts

### 01_Esquema_y_Datos.sql

Incluye:

* Creación de todas las tablas del sistema.
* Definición de claves primarias y foráneas.
* Restricciones de integridad.
* Inserción de datos de prueba.

### 02_Consultas_Avanzadas.sql

Contiene 20 consultas de análisis y reporteo, incluyendo:

* Productos más vendidos.
* Clientes VIP.
* Análisis mensual de ventas.
* Segmentación RFM.
* Predicción básica de demanda.

### 03_Funciones.sql

Implementa 20 funciones definidas por el usuario para:

* Cálculo de ventas.
* Validaciones.
* Generación de códigos.
* Conversión de monedas.
* Cálculos de impuestos y métricas.

### 04_Seguridad.sql

Incluye:

* Creación de roles.
* Creación de usuarios.
* Asignación de privilegios.
* Restricciones de acceso.

### 05_Triggers.sql

Contiene 20 disparadores destinados a:

* Auditoría.
* Validación de datos.
* Actualización automática de inventario.
* Mantenimiento de consistencia.

### 06_Eventos.sql

Incluye eventos programados para:

* Generación de reportes.
* Limpieza de registros temporales.
* Recalculo de indicadores.
* Mantenimiento general de la base de datos.

### 07_Procedimientos_Almacenados.sql

Implementa 20 procedimientos para:

* Gestión de ventas.
* Gestión de clientes.
* Gestión de inventario.
* Generación de reportes.
* Procesamiento de pagos y devoluciones.

---

## ⚙️ Requisitos Previos

Antes de ejecutar el proyecto asegúrese de contar con:

* MySQL 8.0 o superior.
* Privilegios de administrador en el servidor.
* Event Scheduler habilitado.
* Cliente SQL (MySQL Workbench, DBeaver o equivalente).

---

## 🚀 Instrucciones de Ejecución

Ejecute los archivos en el siguiente orden:

```sql
01_Esquema_y_Datos.sql
02_Consultas_Avanzadas.sql
03_Funciones.sql
04_Seguridad.sql
05_Triggers.sql
06_Eventos.sql
07_Procedimientos_Almacenados.sql
```

### Orden recomendado

1. Crear estructura y datos iniciales.
2. Crear consultas avanzadas.
3. Crear funciones.
4. Configurar seguridad.
5. Implementar triggers.
6. Configurar eventos.
7. Crear procedimientos almacenados.

---

## 🔒 Seguridad Implementada

El sistema incorpora múltiples niveles de seguridad:

* Administración completa del sistema.
* Accesos diferenciados por roles.
* Restricciones de modificación de datos críticos.
* Auditoría de cambios.
* Protección de información sensible.
* Control de acceso basado en privilegios.

---

## 📊 Funcionalidades Analíticas

La solución permite generar información estratégica como:

* Ranking de productos.
* Análisis de comportamiento de clientes.
* Tendencias de ventas.
* Rendimiento de proveedores.
* Segmentación de clientes.
* Indicadores de rentabilidad.

---

## ✅ Resultado Esperado

Al ejecutar todos los scripts, se obtendrá una base de datos completamente funcional para un entorno E-commerce, incluyendo:

* Modelo relacional completo.
* Datos de prueba.
* Consultas avanzadas.
* Funciones personalizadas.
* Procedimientos almacenados.
* Triggers de auditoría e integridad.
* Eventos automáticos.
* Sistema de seguridad basado en roles.

---

## 📌 Observaciones

Este proyecto fue desarrollado con fines académicos para demostrar competencias avanzadas en diseño y administración de bases de datos relacionales utilizando SQL.
