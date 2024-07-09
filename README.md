# Enquiry App 📞📋

Welcome to the **Enquiry App**! This application allows users to enter their name, phone number, and subject of enquiry, which is then stored in a SQLite database. Admins can view and manage these enquiries through an admin panel.

## Features ✨

- **User-friendly Form**: Users can easily submit their enquiries by filling out a simple form.
- **SQLite Database**: All enquiries are securely stored in a SQLite database.
- **Admin Panel**: Admins can view and manage all submitted enquiries through a dedicated admin panel.

## Getting Started 🚀

### Prerequisites 📋

- Python 3.x
- SQLite

### Installation 🛠️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/enquiry-app.git
   cd enquiry-app
2.**Install dependencies:**
 pip install -r requirements.txt
3. **Run database migrations**
python manage.py migrate
4.**Create a superuser for the admin panel**
python manage.py createsuperuser
5.**Run the application**
python manage.py runserver

## Usage 📋
1.Open your web browser and navigate to http://127.0.0.1:8000.

2.Fill out the enquiry form with your name, phone number, and subject, then submit.

3.Admins can log in to the admin panel at http://127.0.0.1:8000/admin to view and manage enquiries.

## Contributing 🤝
I welcome contributions! Please fork the repository and submit a pull request.
