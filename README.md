# City Weather Identifier

**Status: 🛑 Paused — active development on this project is on hold while focusing on school and working on other projects.**

A web app that allows users to find detailed weather information for cities across the globe. Built with **Flask**, **HTML/CSS/JS**, and deployed on **Vercel**.

---

## ⏳ Project History
This web app is the final version of a three-part evolution:
1. **[Jordan Weather Legacy v1](https://github.com/saifkayyali3/JordanWeatherIdentifier-v1)** - The Prototype: First Python GUI using static File I/O.
2. **[City Weather Identifier v2](https://github.com/saifkayyali3/City-Weather-Identifier-v2)** - Data Viz: Desktop app with live API integration and Seaborn/Matplotlib graphs. 
3. **City Weather Identifier v3 (This Repo)** - Full-Stack: Responsive web app with Flask backend and Pandas data processing.

---

## Features

- Retrieve current temperature or hourly/daily weather statistics for any city.
- Data Granularity: Unlike v2's weekly overview, v3 provides high-resolution hourly data using Pandas for backend processing
- Responsive design – works on mobile, tablet, and desktop.
- Smart Validation: Filters out non-city regions to ensure data accuracy.

---

## Live Demo

Check out the app here: [City Weather Identifier](https://city-weather-identifier.vercel.app/)

---

## Technologies Used

- **Backend:** Python 3.13, Flask  
- **APIs:** Geopy (Nominatim), Open-Meteo, Timezonefinder 
- **Data Processing:** Pandas  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Deployment:** Vercel  

---

## Getting Started

Follow these steps to run the project locally:

# 1. Clone the repository and enter:
```bash
git clone https://github.com/saifkayyali3/CityWeatherIdentifier.git
cd CityWeatherIdentifier
```
# 2. Make a virtual environment
```bash
python -m venv venv

source venv/bin/activate # Linux/macOS
venv\Scripts\activate # Windows
```

# 3. Install the needed requirements
```bash
pip install -r requirements.txt
```

# 4. Run
```bash
python main.py

```
## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## Author

**Saif Kayyali**

