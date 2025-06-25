# Venta-de-tiempos-Privados
Sistema web para administrar ventas de lotería y tiempos, con gestión de usuarios, sorteos, facturación, reportes y gráficos. Ofrece seguridad, control de acceso y una interfaz moderna, ideal para centralizar y agilizar la operación en varios locales.

# 🎰 Lottery and Sales Management System - Professional Project

This is a professional-grade web application developed using Flask (Python) for managing internal lotteries, number sales, users, and detailed sales reporting. It was built for a business with multiple physical stores, focusing on usability, security, and operational control.

---

## ✅ Main Features

### 1. User Management
- Register, edit, reactivate, and deactivate user accounts.
- Role-based access: Admin and Regular User.
- Route protection using decorators.
- Advanced security: single active session per user.
- Custom forms and validation for active/inactive users.

### 2. Lottery Management
- Create, update, deactivate and reactivate lotteries.
- Business logic for sales limits, re-sell caps, and payment rules.
- Validations for timing, duplicate entries, and constraints.

### 3. Sales and Invoicing
- Track sales of regular and re-sold numbers.
- Validate maximum amounts and business rules.
- Automatically generate detailed invoices.
- Print and reprint invoices.
- Filter invoices by user, date, and lottery.

### 4. Reports and Statistics
- Reports for sales per user, lottery, and date.
- Re-sell activity reports.
- Summary reports and financial balances.
- Interactive charts with Plotly.
- Export and print reporting options.

### 5. Results and Winners
- Record and validate winning numbers.
- Prevent duplicate entries and input errors.
- Search results by date or lottery.

### 6. Admin Panel
- Exclusive access for administrators.
- Full maintenance of users and lotteries.
- Permanent deletion and reactivation of records.
- Advanced filtering and querying of invoices.

### 7. User Interface (Frontend)
- Clean UI using Jinja2 templates.
- Custom responsive CSS for mobile and desktop.
- JavaScript for validations and calculations.
- SweetAlert2 for confirmation and success/error messages.
- Print-friendly styles for invoices and reports.

---

## 🛡️ Security
- Protected routes with Flask decorators.
- Active status check for all users.
- Session management: one active session per user.
- Confirmations before critical actions (e.g., delete, update).

---

## 🧩 Additional Features
- Responsive design for all devices.
- Pagination and filters on queries.
- Exporting of data and reports.
- Real-time balance and earnings calculations.
- Clean, maintainable, and modular codebase.

---

## 🧑‍💻 Technologies Used
- Python 3 / Flask
- SQLite / SQLAlchemy
- Jinja2 Templates
- HTML5 / CSS3 / JavaScript
- Plotly (interactive charts)
- SweetAlert2 (user feedback)

---

## ⚠️ Note
This was developed as my first real-world professional project, built for a client with multiple local businesses. The system is fully functional, scalable, and designed for easy maintenance.

---

## 📸 Screenshots

A collection of images showcasing key features of the system:

---

### 🔐 1. Login Interface
Simple and secure login for users and admins.

![Login](https://github.com/user-attachments/assets/4b41212b-7c82-48b6-b2d3-098981792e20)

---

### 🛒 2. Ticket Sales View
Users can select and buy available numbers or reventados.

![Venta Tiempos](https://github.com/user-attachments/assets/2684cc08-b927-4c1f-98e9-7cbd10e2aab0)

---

### 🧾 3. Invoice Generation
Automated invoices are generated after each sale.

![Facturas](https://github.com/user-attachments/assets/38cd3571-abcf-4fa0-a01f-9d4879fd38a5)

---

### 🖨️ 4. Printable Invoices
Invoices are ready to be printed in a clean format.

![Impresion](https://github.com/user-attachments/assets/38f415bd-17b2-4bf5-bc9e-e1374f782dd6)

---

### 🎯 5. Winning Number Input
Admins can input and register the winning number.

![Numero Ganador](https://github.com/user-attachments/assets/309059d3-7f57-458b-b700-f0703e0af458)

---

### 🥇 6. Winner Invoice View
Winning ticket is highlighted with winner-specific styling.

![Factura Ganadora](https://github.com/user-attachments/assets/37438e00-6f8c-40fe-9cca-c18634675121)

---

### 👤 7. User Sales Report
Admins can filter sales by user, sorteo, and date.

![Reporte Usuario](https://github.com/user-attachments/assets/e417a3b5-60eb-4c9c-913b-b5b139203b10)

---

### 🛠️ 8. Sorteo Management
Admin panel to create, edit, deactivate or reactivate sorteos.

![Mantenimiento Sorteos](https://github.com/user-attachments/assets/4c08c150-a62c-42e3-9176-d8a8b37fe1b1)

---

### 👥 9. User Management
Manage active/inactive users and control roles.

![Mantenimiento Usuarios](https://github.com/user-attachments/assets/0447f156-1c17-4536-a293-c72f046e3331)

---

### 🔎 10. Invoice Filters
Advanced filters for invoice lookup and admin actions.

![Filtros Facturas](https://github.com/user-attachments/assets/d58f9291-642f-42e7-a794-1c0b5d373fd2)

---

### 📊 11. Sales Report
Interactive graphs for visual analysis of sales and reventados.

![Reporte Ventas](https://github.com/user-attachments/assets/d97c5530-ca38-443b-9bcf-cb128001a96a)

---
