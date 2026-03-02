# AGA-Weather-App 🌤️

[![Framework](https://img.shields.io/badge/Framework-WPF-blue.svg)](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/)
[![API](https://img.shields.io/badge/API-AccuWeather-orange.svg)](https://developer.accuweather.com/)
[![Language](https://img.shields.io/badge/Language-C%23-green.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)

### 📝 Description
A sleek and dynamic weather forecasting application built using **WPF**. This project demonstrates how to integrate third-party **REST APIs** into a desktop environment, handling real-time data fetching, JSON parsing, and displaying meteorological information in a user-friendly interface.

---

### ✨ Key Features
* **Real-time Weather Data:** Fetching current conditions and forecasts directly from **AccuWeather**.
* **City Search:** Ability to search for cities globally to get localized weather information.
* **Dynamic UI:** Responsive design that updates based on the retrieved data.
* **Full Documentation:** The codebase is thoroughly documented to explain the logic behind API calls and data binding.

### 🛠️ Code Features
* **API Integration:** Robust handling of HTTP requests and responses.
* **JSON Parsing:** Efficient conversion of API data into C# objects.
* **MVVM Architecture:** Maintaining a clean separation between the UI and the data logic.
* **Async/Await:** Using asynchronous programming to ensure a smooth, non-blocking User Interface.

### 💻 Tech Stack
* **Language:** C#
* **UI Framework:** WPF (.NET)
* **API Provider:** AccuWeather API
* **Data Format:** JSON

---

### ⚠️ Note for Usage & Security
For security and licensing reasons, the API Key has been omitted. To run this application locally, you must use your own developer credentials:

1. **Create an Account:** Register and create your app at [AccuWeather Developer Portal](https://developer.accuweather.com/).
2. **Get API Key:** Copy your unique **API Key**.
3. **Configure Code:** Paste your key as the `API_KEY` string in `ViewModel/Helpers/AccuWeatherHelper.cs`.

> **📌 Important Note:** The AccuWeather free package has limitations (50 calls/day and 1 key/developer). Please keep this in mind during testing.

---

### 🚀 Getting Started
1. Clone the repository.
2. Open the solution in **Visual Studio**.
3. Apply your **AccuWeather API Key** as described above.
4. Build and run the application.

---

### 🤝 Connect with Me
* [LinkedIn](https://linkedin.com/in/agaabdelgawad)
* [GitHub Profile](https://github.com/agaabdelgawad)

---
*If you find this project useful for learning API integration in WPF, feel free to give it a ⭐!*
