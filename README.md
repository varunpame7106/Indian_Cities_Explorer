# Indian Cities Explorer

A Streamlit-based web application that helps users explore Indian cities by providing **real-time weather updates**, **5-day weather forecasts**, **tourist attractions**, and **local food recommendations**.

## ✨ Features

- 🌤️ Real-time weather information
- 📈 5-Day weather forecast with interactive charts
- 🏛️ Tourist attractions for Indian cities
- 🍛 Famous local food recommendations
- 📊 Interactive data visualization using Plotly
- 📂 Excel-based tourism and food database
- 🎯 Clean and user-friendly Streamlit interface

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly**
- **Requests**
- **OpenWeatherMap API**

---

## 📁 Project Structure

```
Indian-Cities-Explorer/
│
├── app.py                  # Main Streamlit application
├── utils.py                # Helper functions
├── attached_assets/
│   └── India_Top_Cities_Tourism_and_Food.xlsx
├── pyproject.toml
├── uv.lock
└── README.md
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Indian-Cities-Explorer.git
```

### 2. Navigate to the Project Folder

```bash
cd Indian-Cities-Explorer
```

### 3. Create a Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install streamlit pandas requests plotly openpyxl
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🌍 API Used

This project uses the **OpenWeatherMap API** to fetch live weather information.

You can generate your own API key here:

https://openweathermap.org/api

---

## 📊 Data Source

Tourism and food recommendation data is stored in:

```
attached_assets/India_Top_Cities_Tourism_and_Food.xlsx
```

---

## 🎯 How It Works

1. Enter the name of an Indian city.
2. The application fetches:
   - Current weather
   - Temperature
   - Humidity
   - Wind Speed
   - Pressure
3. Displays a 5-day weather forecast.
4. Shows tourist attractions.
5. Recommends famous local foods.

---

## 📸 Screenshots

You can add screenshots here.

```
screenshots/home.png
screenshots/weather.png
screenshots/forecast.png
```

---

## 🔮 Future Enhancements

- 🗺️ Google Maps integration
- 📍 Nearby tourist locations
- ❤️ Favorite cities
- 🌙 Dark mode
- 🏨 Hotel recommendations
- ✈️ Travel planner
- AI-based travel recommendations

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Varun Pame**

B.Tech Information Technology  
Vishwakarma Institute of Technology (VIT), Pune

GitHub: https://github.com/varunpame7106

---

⭐ If you found this project useful, don't forget to **Star** the repository!
