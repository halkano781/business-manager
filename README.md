# Business Manager

A modern all-in-one business management system for shop owners and landlords. Manage inventory, sales, customer debts, rental properties, expenses, and M-Pesa transactions from a single mobile-friendly platform.

---

## ✨ Features

### 🏪 Shop Management

- Product inventory management
- Sales recording (Cash, M-Pesa & Credit)
- Customer management
- Customer debt tracking
- Supplier management
- Purchase management
- Expense tracking
- Profit calculation
- Low stock alerts
- Barcode support *(Coming Soon)*

### 🏠 Rental Management

- Property management
- House/unit management
- Tenant management
- Rent collection
- Rent arrears tracking
- Late payment penalties
- Vacancy tracking
- Payment history
- Tenant reminders *(SMS/WhatsApp)*

### 💳 M-Pesa Integration

- Automatic payment confirmation
- Daraja API integration
- Transaction reconciliation
- STK Push *(Planned)*
- Payment history

### 📊 Reports & Analytics

- Daily sales reports
- Weekly reports
- Monthly reports
- Profit & Loss
- Expense reports
- Inventory valuation
- Cash flow summary
- Business dashboard

### 🔒 Security

- Secure authentication
- Role-based access control
- Password encryption
- Audit logs
- Automatic backups

---

## 📱 Screens

- Dashboard
- Shop
- Inventory
- Sales
- Customers
- Suppliers
- Expenses
- Rentals
- Tenants
- Reports
- Settings

---

## 🛠 Tech Stack

### Frontend

- React
- Tailwind CSS
- React Router
- Axios

### Backend

- Node.js
- Express.js
- JWT Authentication

### Database

- PostgreSQL

### Deployment

- Docker
- Railway
- Render
- Supabase

---

## 📂 Project Structure

```text
balesa-business-manager/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   └── package.json
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── docs/
├── docker-compose.yml
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/halkano781/balesa-business-manager.git
cd balesa-business-manager
```

### Install Frontend

```bash
cd frontend
npm install
npm run dev
```

### Install Backend

```bash
cd ../backend
npm install
npm run dev
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the `backend` directory.

```env
PORT=5000

DATABASE_URL=

JWT_SECRET=

MPESA_CONSUMER_KEY=
MPESA_CONSUMER_SECRET=
MPESA_SHORTCODE=
MPESA_PASSKEY=
```

---

## 📅 Roadmap

- [x] Project Planning
- [ ] Authentication
- [ ] Dashboard
- [ ] Inventory Module
- [ ] Sales Module
- [ ] Customer Debt Management
- [ ] Supplier Management
- [ ] Rental Module
- [ ] Reports & Analytics
- [ ] M-Pesa Integration
- [ ] SMS Notifications
- [ ] WhatsApp Notifications
- [ ] Barcode Scanner
- [ ] Progressive Web App (PWA)
- [ ] Android App
- [ ] AI Sales Insights

---

## 🌟 Future Features

- Multi-branch support
- Employee management
- Payroll
- Receipt printing
- QR Code receipts
- Offline mode with automatic sync
- Stock forecasting
- AI-powered business insights

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push your branch.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Halkano Racha Tacho**

- GitHub: https://github.com/halkano781

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub to support its development.
