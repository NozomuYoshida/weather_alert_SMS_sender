# weather_alert_SMS_sender
This is a waather alert SMS sender. 

## Function
- It sends you SMS when it will rain for upcoming 12 hours.

## Usage
- Set your own api key of OpenWeather: https://openweathermap.org/
  - This program needs api key of OpenWeather: https://openweathermap.org/
  - To run, replace API_KEY to your own api key (registration needed)
  - Replace ```os.environ.get('OWM_API_KEY')``` to your own api key
- Set your own authentification token of Twilio: https://console.twilio.com/
  -  Replace ```os.environ.get('AUTH_TOKEN')``` to your own api token
- To run automatically, Python anywhere is recommended: https://www.pythonanywhere.com/
  - Set to run the main.py as the the daily task

## Environment
- MacOS (11.52)
- PyCharm 2021.02 (Community Edition)
