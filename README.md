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

