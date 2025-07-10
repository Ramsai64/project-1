# Project 1: Expense Tracker Web App

A responsive and interactive web-based application that helps users track their income, expenses, and savings. This app is built using HTML, CSS, and JavaScript, and it uses `localStorage` to persist data across sessions without a backend.

## Live Pages

- `index.html` – Login and Register page
- `welcome.html` – Personalized welcome screen after login
- `home.html` – Dashboard with navigation to:
  - `income.html` – Income management
  - `expense.html` – Expense tracking with edit and filter features
  - `saving.html` – Savings summary with pie chart

---

## Features

- Authentication System (localStorage based)  
  Allows user registration and login without a backend.

- Welcome Page  
  Displays a personalized greeting using stored user data.

- Income Tracker  
  Add and view income entries by type (daily, monthly, yearly).

- Expense Tracker  
  Add, edit, delete, and filter expenses by category or date.

- Savings Dashboard  
  Shows a visual summary of income vs. expenses with a pie chart.

---

## Technologies Used

- HTML5 and CSS3  
  For layout, structure, and responsive design.

- Vanilla JavaScript  
  Handles interactivity, logic, and data manipulation.

- Chart.js (via CDN)  
  Used for visualizing savings as a pie chart.

- LocalStorage  
  Ensures data persistence across sessions without requiring a server.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
