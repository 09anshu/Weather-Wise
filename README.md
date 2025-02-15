Weather Wise

🌦️ About

Weather Wise is a simple and responsive weather forecast web application that allows users to search for real-time weather conditions by entering a city name. The app fetches weather data from the WeatherAPI and displays temperature, humidity, wind speed, and weather conditions with an animated UI.

🚀 Features

🌍 Search for any city's weather

🌡️ Displays real-time temperature, humidity, wind speed, and weather conditions

🖼️ Dynamic weather icons based on conditions

🎨 Beautiful UI with animated effects

🔍 Responsive design for mobile and desktop

🛠️ Technologies Used

HTML5

CSS3 (including Tailwind and Google Fonts)

JavaScript (ES6+)

WeatherAPI (for fetching weather data)

📦 Setup & Installation

Clone the repository:

 git clone https://github.com/09anshu/Weather-Wise.git

Navigate to the project directory:

 cd Weather-Wise

Open the index.html file in a browser:

Simply double-click index.html or

Run a live server in VS Code (recommended)

🖥️ Usage

Open the app in your browser.

Enter a city name in the search bar.

Click the Search button.

View real-time weather updates with animated effects.

🌍 API Integration

This app uses WeatherAPI to fetch real-time weather data. Ensure your API key is valid before using the app.

To update the API key in index.html, replace:

const response = await fetch(`http://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${city}&aqi=yes`);

with your actual API key.

🤝 Contributing

Feel free to fork the repository and contribute by submitting pull requests.

📜 License

This project is licensed under the MIT License.

Happy coding! 🚀
