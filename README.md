# Farm Management App

This Django DRF application allows a farmer to manage animals on their farm. The farmer can list, add, and remove animals from the system.

## Setup

1. Clone the repository and navigate to the project directory:

    ```bash
    git clone <repository_url>
    cd farm
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Run the development server:

    ```bash
    python manage.py runserver
    ```

## API Endpoints

- List and Add Animals: `http://127.0.0.1:8000/api/animals/`
- Remove Animal: `http://127.0.0.1:8000/api/animals/<animal_id>/`
