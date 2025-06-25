# 🎰 Sistema de Gestión de Sorteos y Ventas - Proyecto Profesional

Este proyecto es una aplicación web desarrollada con Flask (Python) que permite la gestión integral de sorteos, ventas de números, usuarios y reportes de facturación. Fue diseñado para una cadena de locales comerciales que maneja sorteos internos y control de premios, con foco en facilidad de uso, seguridad y eficiencia operativa.

---

## ✅ Funcionalidades Principales

### 1. Gestión de Usuarios
- Registro, edición, reactivación y desactivación de cuentas.
- Roles diferenciados: administrador y usuario estándar.
- Control de acceso mediante decoradores.
- Seguridad avanzada: una sesión activa por usuario.
- Validaciones y formularios personalizados.

### 2. Gestión de Sorteos
- Creación, modificación y eliminación de sorteos.
- Lógica para límites de ventas, números reventados y montos máximos.
- Validaciones de horario, duplicados y reglas de negocio.

### 3. Ventas y Facturación
- Registro de ventas normales y reventadas.
- Validación automática de montos y disponibilidad.
- Generación de facturas detalladas.
- Impresión y reimpresión de facturas.
- Filtros por usuario, sorteo y fecha.

### 4. Reportes y Estadísticas
- Reportes de ventas totales y reventadas.
- Visualización por usuario, sorteo o fecha.
- Gráficos interactivos con Plotly.
- Exportación e impresión.

### 5. Resultados y Ganadores
- Registro de números ganadores por sorteo.
- Validaciones anti-duplicado.
- Consulta de resultados pasados.

### 6. Panel de Administración
- Vista exclusiva para administradores.
- Mantenimiento de usuarios y sorteos.
- Reactivación o eliminación definitiva.
- Búsquedas y filtros avanzados en facturas.

### 7. Interfaz de Usuario (Frontend)
- Uso de plantillas Jinja2.
- CSS personalizado y responsive.
- JavaScript para interacción y validaciones.
- SweetAlert2 para alertas visuales.
- Estilos de impresión optimizados.

---

## 🛡️ Seguridad
- Decoradores para protección de rutas.
- Validación de usuarios activos.
- Sesión única por usuario.
- Confirmaciones para acciones críticas.

---

## 🧩 Extras Técnicos
- Diseño adaptado a móvil y escritorio.
- Paginación en reportes y consultas.
- Exportación de datos.
- Estilo e impresión profesional de facturas.
- Código modular y documentado.

---

## 🧑‍💻 Tecnologías Utilizadas
- Python 3 / Flask
- Jinja2
- SQLite / SQLAlchemy
- HTML5 / CSS3 / JavaScript
- Plotly
- SweetAlert2

---

## ⚠️ Nota
Este proyecto fue desarrollado como mi primer sistema profesional completo, aplicado a un entorno real de negocio (supermercados y locales). El enfoque fue 100% funcional, robusto y escalable.

---

## 📸 Capturas de Pantalla

Una colección de imágenes que muestran las funciones clave del sistema:

---

### 🔐 1. Pantalla de Inicio de Sesión
Inicio de sesión seguro para usuarios y administradores.

![Login](https://github.com/user-attachments/assets/4b41212b-7c82-48b6-b2d3-098981792e20)

---

### 🛒 2. Venta de Tiempos
Selección y compra de números y reventados.

![Venta Tiempos](https://github.com/user-attachments/assets/2684cc08-b927-4c1f-98e9-7cbd10e2aab0)

---

### 🧾 3. Generación de Factura
Facturas automáticas con los detalles de la compra.

![Facturas](https://github.com/user-attachments/assets/38cd3571-abcf-4fa0-a01f-9d4879fd38a5)

---

### 🖨️ 4. Factura Lista para Imprimir
Diseño limpio y preparado para impresión directa.

![Impresión](https://github.com/user-attachments/assets/38f415bd-17b2-4bf5-bc9e-e1374f782dd6)

---

### 🎯 5. Registro del Número Ganador
Ingreso manual del número ganador por parte del administrador.

![Número Ganador](https://github.com/user-attachments/assets/309059d3-7f57-458b-b700-f0703e0af458)

---

### 🥇 6. Vista de Factura Ganadora
Factura destacada en caso de acierto.

![Factura Ganadora](https://github.com/user-attachments/assets/37438e00-6f8c-40fe-9cca-c18634675121)

---

### 👤 7. Reporte de Ventas por Usuario
Consulta filtrada por usuario, sorteo o fecha.

![Reporte Usuario](https://github.com/user-attachments/assets/e417a3b5-60eb-4c9c-913b-b5b139203b10)

---

### 🛠️ 8. Mantenimiento de Sorteos
Gestión completa de sorteos: crear, modificar, desactivar o reactivar.

![Mantenimiento Sorteos](https://github.com/user-attachments/assets/4c08c150-a62c-42e3-9176-d8a8b37fe1b1)

---

### 👥 9. Mantenimiento de Usuarios
Activación, desactivación y edición de usuarios y roles.

![Mantenimiento Usuarios](https://github.com/user-attachments/assets/0447f156-1c17-4536-a293-c72f046e3331)

---

### 🔎 10. Filtros de Facturas
Búsqueda avanzada y filtros para consultar ventas y facturas.

![Filtros Facturas](https://github.com/user-attachments/assets/d58f9291-642f-42e7-a794-1c0b5d373fd2)

---

### 📊 11. Reporte de Ventas
Gráficos interactivos para el análisis de ventas y reventados.

![Reporte Ventas](https://github.com/user-attachments/assets/d97c5530-ca38-443b-9bcf-cb128001a96a)

---
