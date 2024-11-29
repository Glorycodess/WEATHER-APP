WEATHER APP🌤️

A web application providing real-time weather updates for any city using the OpenWeatherMap API.

FEATURES
1. Displays temperature, humidity, wind speed, and weather conditions.
2. Search functionality to find weather by city.
3. Dynamic backgrounds that change with weather conditions.


RUNNING LOCALLY
1. Clone the repository:
bash
Copy code
git clone https://github.com/your-username/weather-app.git  
cd weather-app  
2. Get a free API key from OpenWeatherMap and replace YOUR_API_KEY in script.js.
3. Open index.html in your browser.

DEPLOYMENT
1. Upload app files to Web01 and Web02 with Nginx installed.
2. Configure Lb01 to load-balance traffic between Web01 and Web02.
