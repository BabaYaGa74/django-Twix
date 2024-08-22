
---

# Twix

Twix is a simple Django-based application that allows users to register, log in, create tweets, edit tweets, delete tweets, and search for tweets. This project was created as my first Django project to learn the basics of Django web development.

## Features

- **User Authentication:** Users can register and log in to the platform.
- **Tweet Management:** Users can create, edit, and delete their tweets.
- **Tweet Search:** Users can search for tweets by text.
- **Tweet Content:** Tweets can be simple text or text with an image.
- **Image Management:** The application uses [Pillow](https://python-pillow.org/) for handling image uploads.
- **Responsive Design:** The application uses [Bootstrap](https://getbootstrap.com/) for styling, ensuring modern interface.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/BabaYaGa74/django-twix.git
   cd twix
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

## Usage

- **Register/Login:** Create an account or log in to access the application.
- **Create a Tweet:** Click on "Create Tweet" to post a new tweet. You can add an image if desired.
- **Edit/Delete a Tweet:** Edit or delete your tweets from your profile.
- **Search Tweets:** Use the search bar to find tweets by keywords.

## Technologies Used

- **Django:** Web framework for building the application.
- **Pillow:** Python Imaging Library for managing images.
- **Bootstrap:** CSS framework for beautiful design.
- **SQLite:** Default database for development.

---
