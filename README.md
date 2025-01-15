# Café Management Web Application

Welcome to the **Café Management Web Application**! This project is a collaborative effort to build a feature-rich platform for managing a café's operations, from customer interactions to cashier workflows.

---

## 🌟 Features

### Public Landing Page
- **Home Page**: 
  - A beautifully designed homepage showcasing key information about the café.
  - Intuitive navigation with a responsive toolbar.
- **About Page**: 
  - Comprehensive details about the café, its history, and team members.
- **Contact Us Page**: 
  - Includes address, phone number, and a contact form for customer inquiries.
  - Integrated map view for easy navigation.
- **Menu**: 
  - Displays all food and drink items with prices and customer comments.
  - "Order Now" button for placing orders (dine-in or online).

### Customer Features
- **Cart**: 
  - Add items to a cart and proceed to checkout.
- **Order Tracking**: 
  - View the status of placed orders (e.g., "Under Review," "Preparing," "Served").

### Cashier Panel
- **Dashboard**: 
  - Overview of key statistics such as new messages and recent orders.
- **Order Management**: 
  - Handle new, in-progress, completed, canceled, and paid orders.
  - Archive of all past orders.
- **Table Management**: 
  - View and manage orders for individual tables.
- **Menu Management**: 
  - Add, edit, or remove menu items.
  - Apply discounts and update prices.
- **Receipts**: 
  - Access issued receipts and payment histories.
- **Analytics (Optional)**: 
  - Generate charts for sales trends and order patterns.

---

## ⚙️ Tech Stack
- **Backend**: Django (Python Framework)
- **Frontend**: HTML, CSS, JavaScript (with Tailwind CSS or Bootstrap)
- **Database**: PostgreSQL
- **Version Control**: Git (GitHub Repository)

---

## 📂 Project Structure
```plaintext
├── café_project/
│   ├── settings.py
│   ├── urls.py
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── about.html
│   │   ├── contact.html
│   ├── static/
│       ├── css/
│       ├── js/
│
├── cashier_panel/
│   ├── urls.py
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   │   ├── dashboard.html
│       ├── orders.html
│       ├── receipts.html
│
├── README.md
└── requirements.txt
```

---

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.9+
- PostgreSQL
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Maktab119_Cafe_project_group1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Maktab119_Cafe_project_group1
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure the database settings in `settings.py`.
5. Apply migrations:
   ```bash
   python manage.py migrate
   ```
6. Run the server:
   ```bash
   python manage.py runserver
   ```
7. Access the app at `http://127.0.0.1:8000/`.

---

## 🧪 Testing
- Run test cases:
  ```bash
  python manage.py test
  ```

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributors
- **Team Member 1**: Backend Developer
- **Team Member 2**: Frontend Developer
- **Team Member 3**: Database Designer

---

## 📧 Contact
For any inquiries, please contact us at [email@example.com](mailto:email@example.com).

---

Thank you for checking out our project! We hope you enjoy it as much as we enjoyed building it. 😊
