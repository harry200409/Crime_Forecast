#  Crime Forecast Application

##  Description
A **sophisticated web application** that leverages **historical crime data from Chicago (2012–2017)** to predict **future crime rates** using **Facebook Prophet's** time series forecasting capabilities.  

The system features an **intuitive web interface** built with **Flask** and **Bootstrap**, providing **interactive visualizations** through **Chart.js** and detailed tabular predictions for deeper insights.

---

##  Features
- Time series forecasting using **Facebook Prophet**
- Interactive and user-friendly **Flask web interface**
- Visual representation of forecasts via **Chart.js**
- Tabular display of predicted values for clarity
- Fully **responsive design** powered by **Bootstrap**  

---

##  Prerequisites
-  **Python 3.x**
-  **Virtual environment** (recommended for isolation)

---

##  Installation

1️. **Clone the repository**
```bash
git clone https://github.com/yourusername/crime-forecast-application.git
cd crime-forecast-application
```
2. **Create and activate a virtual environment**
```bash
python -m venv myenv
myenv\Scripts\activate        # Windows
source myenv/bin/activate     # Mac/Linux
```
3. **Install required packages**
```bash
pip install -r requirements.txt
```

## Usage

1. **Run the Flask server**
```bash
python app.py
```
2. **Open your browser and go to**
```bash
http://localhost:5000
```
3. **Enter the number of months for prediction**
4. **View results in an interactive graph & detailed table**

## Project Structure

```text
├── app.py                         # Flask application server
├── forecast.ipynb                 # Jupyter notebook for model development
├── forecast_model.pkl             # Trained Prophet model
├── Chicago_Crimes_2012_to_2017.xls# Historical dataset
├── requirements.txt               # Python dependencies
└── templates/
    └── index.html                 # Web interface template
```

## Technologies Used

- Backend: Python, Flask
- Frontend: HTML, JavaScript, Bootstrap
- Data Analysis: Prophet, Pandas
- Visualization: Chart.js
