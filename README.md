# 💰 Expense Manager

A web-based Expense Manager application to track and manage personal expenses effectively, with features like real-time data visualization, user authentication, and data storage using MongoDB.

---

## 🚀 Features
- 📊 **Expense Tracking** – Add, categorize, and track expenses.
- 🔐 **User Authentication** – Secure login and user-specific data access.
- 📈 **Data Visualization** – Insights using interactive charts (Matplotlib, Plotly, Seaborn).
- 📅 **Real-Time Updates** – Reflect changes instantly without refreshing.
- 🗄️ **MongoDB Integration** – Persistent storage for user data and expenses.

---

## 🛠️ Tech Stack
| Technology | Purpose |
|-----------|---------|
| **Python** | Backend logic |
| **Streamlit** | Frontend framework |
| **MongoDB** | Database |
| **Pandas, Numpy** | Data handling and manipulation |
| **Matplotlib, Plotly, Seaborn** | Data visualization |
| **Bokeh** | Interactive plots |
| **Pillow (PIL)** | Image handling |

---
---

## 🏃‍♂️ Getting Started
### 1. **Clone the Repository**
```bash
git clone https://github.com/SakshithBillava/Expense-Manager.git
```
### 2. **Install dependencies**
```bash
pip install -r requirements.txt
```
🌐 Environment Variables
Create a .env file and add the following:
```ini
MONGO_URI=mongodb+srv://<username>:<password>@cluster-url
SECRET_KEY=<your-secret-key>
```
### 3. **Run the project**
```bash
streamlit run Expense.py
```

🎯 Usage
1. Register or log in.
2. Add expenses with category and amount.
3. View detailed charts and reports.
4. Update or delete records if needed.

🚀 Future Enhancements
1. Automated Expense Classification – Implement machine learning to automatically categorize expenses based on transaction patterns.
2. Budgeting and Forecasting – Add budget-setting features with monthly and yearly expense tracking and future expense forecasting.
3. Recurring Expenses Management – Enable automatic tracking and reminders for recurring expenses like subscriptions and bills.
4. Multi-Currency Support – Allow users to track expenses in different currencies with real-time exchange rate conversion.
5. Offline Mode – Enable offline functionality to log expenses even without an internet connection and sync when online.
6. Data Export and Backup – Provide options to export expense data to CSV, PDF, or Excel, and enable automatic cloud backups.
7. Advanced Analytics and Insights – Integrate deeper insights using AI to identify spending patterns and suggest ways to save money.
8. User Roles and Sharing – Allow multiple user roles and shared access for joint expense tracking (e.g., family or team).


