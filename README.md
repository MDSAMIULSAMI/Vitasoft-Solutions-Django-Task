# Vitasoft-Solutions-Django-Task

# TeamCollab

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone <YOUR_GIT_REPOSITORY_URL>
    cd teamcollab
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the server:
    ```bash
    python manage.py runserver
    ```

## API Documentation

- Swagger: `http://localhost:8000/swagger/`
- Redoc: `http://localhost:8000/redoc/`
