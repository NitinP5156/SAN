# Social Media Platform

A modern social media application built with Django, featuring real-time messaging, user profiles, and feed functionality.

## Features

- User authentication and profile management
- News feed with posts and comments
- Real-time messaging with other users
- Follow/unfollow functionality
- Responsive design for mobile and desktop

## Tech Stack

- Django (Backend)
- HTML/CSS/JavaScript (Frontend)
- Tailwind CSS (Styling)
- SQLite (Database)

## Installation

1. Clone the repository
```bash
git clone https://github.com/NitinP5156/SAN.git
cd SAN
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser
```bash
python manage.py createsuperuser
```

6. Start the development server
```bash
python manage.py runserver
```

## Project Structure

- `core/` - Main application with models, views, and templates
- `social_media/` - Project settings and configuration
- `media/` - User-uploaded content
- `static/` - Static files (CSS, JS, images)

## Screenshots

*Coming soon*

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 