# Contributing to CRUD Django REST Framework

Thank you for considering contributing to this project! Here are some guidelines to help you get started.

## Setting Up Development Environment

1. Fork the repository
2. Clone your fork: `git clone https://github.com/Anas-github-acc/crud_django_rest_framework`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Unix/MacOS: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Apply migrations: `python manage.py migrate`

## Development Workflow

1. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
2. Make your changes
3. Run tests: `python manage.py test`
4. Commit your changes with a descriptive message
5. Push to your fork: `git push origin feature/your-feature-name`
6. Create a Pull Request against the main repository

## Code Style

- Follow PEP 8 guidelines
- Use docstrings for functions and classes
- Write meaningful commit messages

## Reporting Issues

When reporting issues, please include:

- Detailed description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Django and DRF versions

## Pull Request Process

1. Ensure your code follows the project's style guidelines
2. Update documentation if necessary
3. Add tests for new features
4. Make sure all tests pass
5. Your PR will be reviewed by maintainers

Thank you for your contributions!
