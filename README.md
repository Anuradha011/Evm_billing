# Evm_billing

A Django-based billing application.

> This project is in its early stages — currently a standard Django project scaffold (`mysite`). This README covers setup and will grow as models, apps, and features are added.

## Tech Stack

- Python 3.x
- Django

## Project Structure

```
Evm_billing/
├── manage.py
└── mysite/
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    ├── asgi.py
    └── wsgi.py
```

## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Anuradha011/Evm_billing.git
   cd Evm_billing
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install django
   ```
   > If a `requirements.txt` is added later, use `pip install -r requirements.txt` instead.

4. Apply migrations
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional, for admin access)
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server
   ```bash
   python manage.py runserver
   ```

7. Visit the app at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Roadmap

- [ ] Add a Django app for billing logic (e.g. `billing/`)
- [ ] Define models for invoices, customers, and transactions
- [ ] Add `requirements.txt`
- [ ] Add admin panel configuration
- [ ] Add tests

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

No license specified yet. Consider adding one (e.g. MIT) if this project is meant to be open source.
