# Basic Django Blog Project

A feature-rich blog application built with Django, incorporating user authentication and post management capabilities.

## Features

- User Authentication using Ion OAuth
- Create, Read, Update, and Delete blog posts
- Responsive design with Bootstrap
- User-specific post management
- Clean and intuitive user interface

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YousafZahid1/basicdjango.git
cd basicdjango
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create a superuser (optional):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Project Structure

```
basicdjango/
├── assignment_blog/     # Main project directory
├── blog/               # Blog application
│   ├── templates/      # HTML templates
│   ├── models.py       # Database models
│   ├── views.py        # View logic
│   └── urls.py         # URL routing
├── ion_auth/          # Authentication app
└── manage.py          # Django management script
```

## Features in Detail

### Authentication
- Secure login using Ion OAuth
- User session management
- Protected routes and views

### Blog Management
- Create new blog posts
- View all posts
- Edit existing posts
- Delete posts
- Post detail view

### User Interface
- Responsive design
- Bootstrap-based styling
- Clean and intuitive navigation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Yousaf Zahid - [GitHub Profile](https://github.com/YousafZahid1)

Project Link: [https://github.com/YousafZahid1/basicdjango](https://github.com/YousafZahid1/basicdjango)
