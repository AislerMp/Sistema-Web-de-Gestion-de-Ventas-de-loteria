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

