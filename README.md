
# Movies Store

Movies store is a Django web application for movies. This application is the running example of the book “Django 5 for the Impatient - Second Edition”. 

## Requirements

- Python 3.10
- Django 5.0

## Environment Variables
Use the ".env.example" file to add the required environment variables.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kristianrpo/movies-store.git
   cd movies-store
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

## Usage

- Access the application at `http://127.0.0.1:8000/` in your web browser.
