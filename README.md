# Python Bootcamp & Hackathon

## Weather App

This is a Python Django project for a weather app that allows users to search for cities and get temperature readings along with the current date and location. The app utilizes the Open Weather API to fetch weather data for the searched cities.

### Features

- **Search Bar**: Users can search for cities using the search bar feature.
- **Temperature Readings**: The app provides temperature readings for the searched cities.
- **Location and Current Date**: The app displays the location (city) and current date along with the temperature readings.
- **Background Images**: Background images related to the searched place are displayed to enhance the user experience.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git
```

2. Navigate to the project directory:

```bash
cd weather-app
```

3. Obtain an API key from Open Weather API and replace YOUR_API_KEY in settings.py with your API key.


4 .Run migrations:

```bash
python manage.py migrate
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Open your web browser and go to http://127.0.0.1:8000/ to view the app.


### Usage

1. Enter the name of the city you want to get weather information for in the search bar.
2. Click on the search button.
3. The app will display the temperature readings, location (city), current date, and background images related to the searched place.

### Technologies Used
- Python
- Django
- Open Weather API

### Credits

This project was created by [daniel-caleb]. It utilizes the Open Weather API for fetching weather data. [https://openweathermap.org/api]

### License
This project is licensed under the MIT License.
