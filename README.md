#  FinanceTracker

**FinanceTracker** is a full-featured **Django web application** designed to help users manage personal finances with ease. It offers secure user authentication, transaction tracking, goal setting, and insightful reporting—all in one intuitive dashboard.

---

##  Key Features

1. **Secure User Accounts**
   - User registration and login (with optional email confirmation or third-party integration).
   - Secure password handling (hashed and encrypted).

2. **Manage Transactions**
   - Add income and expense transactions with details (date, amount, category, description).
   - Edit or delete past transactions.

3. **Transaction History**
   - Comprehensive transaction log with filtering by date, category, and amount.
   - Sortable and paginated for easy browsing.

4. **Visual Insights & Reporting**
   - Generate detailed financial reports such as spending breakdowns, income vs. expenses charts.
   - Downloadable report formats (CSV, PDF) for sharing or offline record keeping.

5. **Set Financial Goals**
   - Create and track goals (e.g., "Save ₹10,000 for a laptop").
   - Visual progress indicators (e.g., progress bars or charts).

6. **Dashboard Overview**
   - Quick-view stats: total balance, recent transactions, goal progress, etc.
   - Customizable cards/widgets for a personalized experience.

7. **Responsive Design**
   - Works smoothly across devices (desktop, tablet, mobile), using standard HTML/CSS or frameworks like Bootstrap/Tailwind.

---

##  Tech Stack

- **Backend**: Django 5+ (Python 3.12+)
- **Frontend**: HTML, CSS,  Tailwind CSS
- **Database**: SQLite (default) 
- **Key Django Packages**:
  - `django-crispy-forms` (for better form handling)
  - `django-filter` (for enhanced filtering functionality)
  - `plotly-django` / `chart.js` / `matplotlib` (for visual reports)

---

##  Installation & Setup

Run the following commands to get the project running locally:

git clone https://github.com/sanij0579/FinanceTracker.git
cd FinanceTracker
python3 -m venv env
source env/bin/activate  # (Linux/Mac)
# env\Scripts\activate   # (Windows)
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser  # (optional, for admin access)
python manage.py runserver
Access the app at: http://127.0.0.1:8000/

Usage Guide
Student Flow
	1.	Sign up and log in to access your personalized dashboard.
	2.	Add income or expenses with relevant details (date, category, amount).
	3.	View your transaction history—filter by date, category, and amount.
	4.	Set financial goals and track your progress visually.
	5.	Generate and download comprehensive reports for insight and tracking.

Admin/Reception Flow
	1.	Log into Django admin (if enabled).
	2.	View and manage all users, transactions, goals, and reports.
	3.	Export data or provide support as needed.

Advanced Features (Optional Enhancements)
	•	Email Notifications – Reminders for upcoming goals or weekly summaries.
	•	Budget Alerts – Get warnings if exceeding a certain spending limit.
	•	Recurring Transactions – Automate weekly/monthly recurring inputs.
	•	Multiple Accounts – Track separate accounts (e.g., savings, credit card).

⸻

Contributing

Contributions are welcome! Here’s how you can help:
	1.	Fork the repository.
	2.	Create a new feature branch:
 git checkout -b feature-name
 	3.	Commit your changes:
  git commit -m "Add awesome feature"
  	4.	Push to your branch:
   git push origin feature-name
   	5.	Submit a Pull Request.
    Contact

Questions, feedback, or improvements? Reach out:
	•	Author: Sani Jain
	•	GitHub: @sanij0579
	
