# ERP-Based-Business-Management-System-for-Warehouse-and-Financial-Operations-WarehouseMS-

WarehouseMS is a modular ERP-based web application built to manage warehouse operations and financial workflows for multi-branch distribution businesses.

🚀 Key Features
Multi-branch (multi-tenant) architecture with global query scoping
Role-based access control (Owner, Finance, Admin)
Multi-level approval workflow (Purchase Order & Petty Cash)
Real-time stock management with automatic updates
Sales billing with partial payment support
Running balance calculation for financial tracking
PDF report generation (stock, transactions, sales reports)
🏗️ System Highlights
Multi-Tenancy: Implemented using Global Eloquent Scope (WilayahScope) for automatic data isolation per branch
Data Integrity: Critical operations wrapped in database transactions
Locked Pricing: Ensures historical pricing consistency for sales records
Approval Workflow Engine: Status-based flow with role-specific actions
🛠️ Tech Stack
Backend: Laravel 11 (PHP 8.x)
Database: MySQL
Frontend: Blade + Tailwind CSS
Tools: Vite, DomPDF
📊 Use Case

Designed for distribution companies needing integrated control over warehouse inventory, financial approvals, and sales transactions across multiple branches.
