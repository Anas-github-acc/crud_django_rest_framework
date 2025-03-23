# Django REST Framework CRUD API

Django REST framework is a powerful and flexible toolkit for building Web APIs.

## Requirements

- Python 3.6
- Django 3.1
- Django REST Framework

## Installation

```bash
python -m venv env
# Activate environment
pip install -r requirements.txt
```

## Features

- Full CRUD functionality (Create, Read, Update, Delete)
- RESTful API with Django REST Framework
- Token-based authentication
- Detailed API documentation
- Pagination support
- Error handling and validation
- Filtering and searching

## API Endpoints

| Endpoint   | HTTP Method | CRUD Method | Result             |
| ---------- | ----------- | ----------- | ------------------ |
| movies     | GET         | READ        | Get all movies     |
| movies/:id | GET         | READ        | Get a single movie |
| movies     | POST        | CREATE      | Create a new movie |
| movies/:id | PUT         | UPDATE      | Update a movie     |
| movies/:id | DELETE      | DELETE      | Delete a movie     |

## Usage

```bash
python manage.py runserver
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines on how to contribute to this project.
