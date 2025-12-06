# Slooze Commodities Management System

A modern, lightweight commodities inventory management application with role-based access control.

## 🌐 Live Demo

**[View Live Application](https://garimac-git.github.io/Commodities-Management-Frontend/)**

## 📖 Overview

A single-page application for managing commodity inventory with different access levels for Managers and Store Keepers. Built with vanilla JavaScript (Preact) and Tailwind CSS - no build process required.

## ✨ Features

### Authentication & Authorization
- Secure login system with role-based access
- Two user roles: Manager and Store Keeper
- Protected routes based on user permissions

### Dashboard (Manager Only)
- Real-time inventory statistics
- Total products count
- Inventory value calculation
- Low stock alerts
- Category-wise breakdown

### Product Management
- View all products in a organized table
- Add new products with validation
- Edit existing product details
- Delete products with confirmation
- Fields: Name, Category, Quantity, Price, Supplier

### User Experience
- Light/Dark mode toggle
- Theme preference persistence (localStorage)
- Responsive design for all devices
- Clean, modern UI
- Intuitive navigation

## 🔐 Demo Accounts

### Manager Account
- **Email:** manager@slooze.xyz
- **Password:** manager123
- **Access:** Full dashboard + product management

### Store Keeper Account
- **Email:** keeper@slooze.xyz
- **Password:** keeper123
- **Access:** Product management only

## 🛠️ Technology Stack

- **Frontend:** Preact (3KB React alternative)
- **Styling:** Tailwind CSS (CDN)
- **Storage:** localStorage
- **Icons:** Custom SVG icons
- **Build:** None required - single HTML file

## 🚀 Quick Start

### Option 1: Visit Live Demo
Simply visit the live demo link above - no installation needed!

### Option 2: Run Locally
1. Download `index.html`
2. Open it in any modern browser
3. Start using the application

That's it! No npm, no dependencies, no build process.

## 📂 Project Structure
```
Commodities-Management-Frontend/
├── index.html          # Complete application in one file
└── README.md           # Project documentation
```

## 💡 Key Highlights

- **Zero Dependencies:** Everything bundled in a single HTML file
- **Lightweight:** ~20KB total size
- **Fast:** Instant loading, no build step
- **Modern:** Uses latest web standards
- **Accessible:** Keyboard navigation and ARIA labels
- **Persistent:** Theme and state management

## 🎯 Use Cases

- Warehouse inventory tracking
- Retail stock management
- Supply chain monitoring
- Restaurant ingredient management
- Small business inventory

## 🔒 Security Note

This is a demo application with mock authentication. 

## 🤝 Contributing

This is a personal project, but suggestions are welcome! Feel free to:
- Open issues for bugs
- Suggest new features
- Fork and experiment
