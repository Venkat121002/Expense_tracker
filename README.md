# Expense Tracker

## Overview
The Expense Tracker is a full-stack web application designed to help users manage their finances efficiently. The application allows users to track their income and expenses, categorize them, and visualize their spending patterns over different timeframes.

---

## Features

- **User Authentication:**
  - Secure registration and login system.
  - Session management for personalized user experience.

- **Expense and Income Tracking:**
  - Add, update, and delete financial records.
  - Categorize transactions as Income or Expense.

- **Data Visualization:**
  - Generate insights with graphs and charts.
  - Analyze weekly, monthly, and yearly financial trends.

- **Responsive Design:**
  - Accessible across devices with a user-friendly interface.

---

## Technologies Used

### Frontend:
- HTML, CSS, JavaScript
- Bootstrap for responsive design

### Backend:
- Python
- Django Framework

### Database:
- MySQL for data storage

---

## Installation and Setup

### Prerequisites:
- Python (version 3.8 or above)
- MySQL
- Django (version 4.0 or above)

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
   ```

2. Set up a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Configure the database:
   - Create a MySQL database named `expense_tracker`.
   - Update the database credentials in `settings.py`:
     ```python
     DATABASES = {
         'default': {
             'ENGINE': 'django.db.backends.mysql',
             'NAME': 'expense_tracker',
             'USER': 'your-username',
             'PASSWORD': 'your-password',
             'HOST': 'localhost',
             'PORT': '3306',
         }
     }
     ```

4. Apply migrations and start the server:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```

5. Access the application in your browser at `http://127.0.0.1:8000`.

---

## Usage

1. **Register/Login:** Create an account or log in with your credentials.
2. **Add Transactions:** Enter income and expenses with categories, dates, and amounts.
3. **View Insights:** Use the dashboard to analyze spending trends and financial health.
4. **Manage Profile:** Edit personal details and financial settings from the profile page.

---

## Screenshots
![Screenshot (45)](https://github.com/user-attachments/assets/895282f6-ac2d-4b46-825a-579b903281ec)
![Screenshot (41)](https://github.com/user-attachments/assets/2aaedd6a-94c0-465c-81b0-303b5e975cfa)



---

## Contribution

Contributions are welcome! If you'd like to improve the project:
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements
- Django Documentation: https://docs.djangoproject.com/
- Bootstrap: https://getbootstrap.com/

---

## Contact
For queries or collaboration:
- Email: your-email@example.com
- GitHub: [your-username](https://github.com/your-username)

---
