```markdown
#🌤️ Coimbatore Weather Prediction App

##Overview
The **Coimbatore Weather Prediction App** is a **Streamlit-based web application** that fetches real-time and historical weather data for Coimbatore. It provides **visualizations, statistical analysis, and machine learning-based forecasts**.

##Features
- 🌐 **Real-Time Weather Data**: Fetches current weather conditions using the WeatherAPI.
- 🔄 **Historical Weather Trends**: Collects past weather data for trend analysis.
- 🌍 **Data Visualization**: Uses **Matplotlib, Seaborn, and Plotly** for interactive charts.
- 🤖 **Machine Learning Forecasting**: Implements **Random Forest Regression** to predict future temperatures.
- 📆 **7-Day Forecast**: Displays weather predictions using API data.
- 🎨 **User-Friendly UI**: Built with **Streamlit** for an interactive experience.
- ⚡ **API Rate Monitoring**: Prevents exceeding API usage limits.

##Installation

###Prerequisites
Ensure you have Python installed on your system (Python 3.8 or later is recommended). You can check your version with:
```sh
python --version
```

### Steps
1. **Clone the repository**:
   ```sh
   git clone https://github.com/Sanjey2005/Weather-Prediction-Streamlit.git
   cd Weather-Prediction-Streamlit
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application**:
   ```sh
   streamlit run streamlit_app.py
   ```

## Configuration
- **WeatherAPI Key**: Sign up at [WeatherAPI](https://www.weatherapi.com/) to get a free API key.
- **Enter the API Key** in the Streamlit sidebar input when running the app.

## Project Structure
```
Weather-Prediction-Streamlit/
│── streamlit_app.py      # Main Streamlit application
│── requirements.txt      # Required dependencies
│── README.md             # Project documentation
│── .gitignore            # Ignore unnecessary files
│── data/                 # (Optional) Store local datasets
│── assets/               # (Optional) Store images, icons, etc.
```

## Dependencies
The required libraries are listed in `requirements.txt`:
```txt
streamlit
pandas
matplotlib
seaborn
numpy
scikit-learn
plotly
requests
statsmodels
```

##Deployed version link

[🔗  Link](https://weather-prediction-app-tzs9mrfzimtenjzczafs9r.streamlit.app/)

## Contact
For any questions, feel free to reach out via:
- **GitHub**: [Sanjey2005](https://github.com/Sanjey2005)
- **Email**: sanjey8105@gmail.com

---
Made with ❤️ using **Streamlit & Machine Learning**!
```

