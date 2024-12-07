
# 🌦️ Weather Forecasting Application

This is a simple Python application that provides real-time weather information for a city of your choice. The application retrieves weather data, including current conditions and temperature, and converts the temperature from Fahrenheit to Celsius for easy understanding.

---

## 🚀 Features

- **Real-Time Weather Data**: Fetches live weather information using the OpenWeatherMap API.
- **Global City Search**: Allows you to search for weather conditions in any city worldwide.
- **Temperature Conversion**: Automatically converts temperatures from Fahrenheit to Celsius.
- **Error Handling**: Notifies the user if the city entered is not found.

---

## 🛠️ Tools & Technologies

- **Python**: Core programming language used.
- **Requests Library**: To fetch data from the OpenWeatherMap API.
- **OpenWeatherMap API**: API used to retrieve weather information.

---

## 📚 How It Works

1. **Input**: The user enters the name of a city.
2. **API Call**: The application sends a request to the OpenWeatherMap API to fetch weather data for the city.
3. **Data Handling**:
   - If the city is found, the weather conditions and temperature are displayed.
   - If the city is not found, an error message is shown.
4. **Temperature Conversion**: The temperature fetched in Fahrenheit is converted to Celsius for display.

---

## 🔑 Prerequisites

1. **Python Environment**:
   - Ensure Python 3.6 or above is installed on your system.
2. **Dependencies**:
   - Install the `requests` library using the command:  
     ```bash
     pip install requests
     ```
3. **API Key**:
   - Obtain an API key from [OpenWeatherMap](https://openweathermap.org/).
   - Replace the placeholder in the code with your API key.

---

## 📝 Usage Instructions

1. Clone or download this repository to your local machine.
2. Replace the placeholder `apikey` variable with your OpenWeatherMap API key.
3. Run the script in your terminal or any Python IDE.
4. Enter the name of the city when prompted, and view the weather details.

---

## 🌐 Example Use Cases

- **Personal Use**: Check the weather in your city or travel destination.
- **Learning Project**: Use this code as a foundation to explore APIs, JSON handling, and Python programming.

---

## 💡 Future Enhancements

- Add support for a 7-day weather forecast.
- Include more weather details like wind speed, humidity, and sunrise/sunset times.
- Enhance the user interface with a web or GUI-based interface.
- Implement location-based automatic weather fetching.

---

## 🤝 Contribution

We welcome contributions! Feel free to fork the repository, make improvements, and submit a pull request. Suggestions and bug reports can be submitted through the Issues section.

![image](https://github.com/user-attachments/assets/c666a20a-43f2-4bff-af96-e0a0dac88bdd)


## 🌟 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing weather data through their API.
- The Python community for creating robust libraries like `requests`.

---
