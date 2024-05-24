<img src="https://socialify.git.ci/ManojKumar2920/Notes-Sharing-Django-Web-Application/image?description=1&descriptionEditable=Notes%20Share%20is%20a%20collaborative%20note-sharing%20application%20built%20with%20Django.%20It%20allows%20users%20to%20create%2C%20share%2C%20and%20manage%20notes%20seamlessly.&forks=1&issues=1&name=1&owner=1&stargazers=1&theme=Light" alt="Notes-Sharing-Django-Web-Application"/>

# Notes Share

Notes Share is a collaborative note-sharing application built with Django. It allows users to create, share, and manage notes seamlessly. Whether you're a student, professional, or just someone who loves to stay organized, NoteShare offers a user-friendly platform to store your thoughts and share them with others.

## Features

- User authentication and registration
- Create, edit, and delete notes
- Categorize notes with tags
- Share notes with other users
- Real-time updates and notifications
- Clean and intuitive user interface

## Screenshots

![Screenshot 1](screenshots/Screenshot2024-04-08171344.png)
![Screenshot 2](screenshots/screenshot2.png)

## Installation

### Prerequisites

- Python 3.x
- Django 3.x
- pip (Python package installer)

### Steps

1. Clone the repository:
   
   ```bash
   git clone https://github.com/yourusername/noteshare.git
   cd noteshare
   ```
   
2. Create and activate a virtual environment:
   
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
   
3. Install the required packages:
   
    ```bash
    pip install -r requirements.txt
   ```

4. Apply the migrations:
   
    ```bash
    python manage.py migrate
   ```

5. Create a superuser:

   ```bash
    python manage.py createsuperuser
   ```

6. Run the development server:
   
   ```bash
    python manage.py runserver
   ```

7. Open your web browser and go to http://127.0.0.1:8000/

## Usage

1. Register a new user account or log in with an existing account.
2. Create new notes and organize them with tags.
3. Share notes with other users by entering their email addresses.
4. Manage your notes from the dashboard, where you can edit or delete them as needed.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
