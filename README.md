# Footbit

Footbit is a full-stack Flask web application built for soccer news, e-commerce, and admin management.

## Core Features

### User Panel
- View latest soccer news
- Shop for soccer-related items
- Add to cart and purchase products
- Download invoices
- Secure login & registration system

### Admin Panel
- Manage users (excluding passwords)
- Manage products and articles directly from the interface
- View sales analytics and purchase summaries
- Export reports (sales, products, articles)
- Update content without modifying source code

## Security
- Password hashing using Werkzeug
- CSRF protection using Flask-WTF
- Session-based authentication with Flask-Login

## Tech Stack
- Python (Flask)
- SQLite3 database
- HTML / CSS / JavaScript
- CSV and text-based file handling
- Binary storage for experimental settings

## Data Handling
- SQLite for structured storage
- CSV for product/article import and export
- Text-based invoices
- Binary storage experiments for future media support

## Planned Improvements
- QR-based payment integration
- Real payment gateway support
- UI improvements
- Expanded settings panel
- Stronger data security
- Potential integration with storage/asset management systems

## Project Status
Work in progress — actively being expanded and improved.

