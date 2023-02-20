# Django Geolocation Project

This is a Django project that uses APIs to get the user's geolocation based on their IP address and displays information about their location on a webpage.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/django-geolocation.git`
2. Navigate to the project directory: `cd django-geolocation`
3. Create a virtual environment: `python3 -m venv env`
4. Activate the virtual environment: `source env/bin/activate` (for Linux/Mac) or `env\Scripts\activate` (for Windows)
5. Install the requirements: `pip install -r requirements.txt`
6. Migrate the database: `python manage.py migrate`
7. Create a superuser: `python manage.py createsuperuser`
8. Run the development server: `python manage.py runserver`

## Usage

1. Open a web browser and go to `http://localhost:8000`
2. Log in with the superuser credentials you created during installation
3. The page will display your current location information, including your IP address, country, city, zip code, latitude, and longitude.

## APIs used

This project uses the following APIs to get the user's geolocation based on their IP address:

- [ip-api](https://ip-api.com/): This API is used to get the user's country, city, and zip code based on their IP address.
- [ipify](https://www.ipify.org/): This API is used to get the user's current IP address.

## Credits

This project was created based on the tutorial from [Code With Tomi]https://www.youtube.com/@CodeWithTomi.
