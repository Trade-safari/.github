# Trade Safari

A modern multi-vendor marketplace platform that enables sellers to create and manage online stores while allowing customers to discover, browse, and purchase products seamlessly.

---

## Overview

Trade Safari is a web-based marketplace designed to connect buyers and sellers through a scalable, secure, and user-friendly platform.

### Key Features

### Customer Features

* Browse products
* Search and filter products
* View seller stores
* Add products to cart
* Secure checkout with Paystack
* Track orders

### Seller Features

* Seller registration
* Store creation and management
* Product management
* Image uploads
* Order tracking
* Sales monitoring

### Admin Features

* User management
* Store management
* Product moderation
* Activity monitoring
* Platform analytics

---

## Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Axios

### Backend

* Supabase
* PostgreSQL

### Authentication

* Supabase Auth

### Storage

* Supabase Storage

### Payments

* Paystack

### Deployment

* Vercel

---

## Project Structure

```text
src/
├── assets/
├── components/
├── pages/
├── layouts/
├── routes/
├── services/
├── hooks/
├── context/
├── utils/
└── features/
    ├── auth/
    ├── products/
    ├── stores/
    ├── orders/
    ├── seller-dashboard/
    └── admin/
```

---

## Development Workflow

### Branch Strategy

```text
main
└── Dev
    ├── feature/auth
    ├── feature/customer-web
    ├── feature/product-catalog
    ├── feature/seller-dashboard
    ├── feature/admin-panel
    └── feature/payments
```

### Rules

* Never push directly to `main`
* Create feature branches from `Dev`
* Open Pull Requests into `Dev`
* Get code reviewed before merging
* Pull latest changes before starting work

---

## Getting Started

### Clone Repository

```bash
git clone <repository-url>
```

### Enter Project Directory

```bash
cd TARDE-SAFARI-WEB
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file in the root directory.

```env
VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
VITE_PAYSTACK_PUBLIC_KEY=
```

Never commit sensitive credentials.

---

## Team Responsibilities

### Frontend Team

* UI implementation
* Routing
* State management
* API integration

### Backend Team

* Database design
* Authentication
* APIs
* Storage management

### UI/UX Team

* Design system
* Wireframes
* Responsive layouts
* User experience design

### DevOps Team

* Repository management
* Branch protection
* Deployment
* Documentation
* CI/CD setup

---

## Current Development Status

* [x] Repository Initialized
* [x] React + Vite Setup
* [ ] UI/UX Design
* [ ] Supabase Setup
* [ ] Authentication
* [ ] Customer Marketplace
* [ ] Seller Dashboard
* [ ] Admin Panel
* [ ] Paystack Integration
* [ ] Deployment

---

## Contribution Guidelines

1. Pull latest changes from `Dev`
2. Create a feature branch
3. Develop your feature
4. Commit changes
5. Push branch
6. Open a Pull Request
7. Wait for review before merging

---

## License

This project is currently being developed as a collaborative team project.

