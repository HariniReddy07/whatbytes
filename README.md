Django User Authentication System
This is a Django web application that implements a user authentication system with features like sign-up, login, password reset, password change, and user profile management.

Features
- User Registration: Allows users to sign up using a username, email, and password.
- User Login: Users can log in with their username/email and password.
- Password Reset: Users can reset their password if they forget it by receiving a password reset email.
- Password Change: Authenticated users can change their password.
- Profile Management: Users can view their profile information (username, email, date joined, last updated).
- Dashboard: Displays a greeting message and quick links to profile and change password.
Technologies Used
- Django: Web framework used for building the application.
- SQLite: Database used to store user data (can be replaced with PostgreSQL, MySQL, etc. in production).
- HTML/CSS: For frontend user interface.
- Bootstrap: For styling and responsiveness.
- Email Functionality: Uses Django's email system to send password reset instructions.

  
Installation

1. Clone the repository:

git clone https://github.com/HariniReddy07/whatbytes.git
cd myproject

2. Install dependencies:

pip install -r requirements.txt

3. Apply migrations to set up the database:

python manage.py migrate

4. Create a superuser to access the Django admin:

python manage.py createsuperuser

5. Run the development server:

python manage.py runserver
Access the app at http://127.0.0.1:8000/.

Screenshots

1. LOGIN PAGE
