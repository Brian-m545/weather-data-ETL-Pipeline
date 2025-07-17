
# Nairobi Weather ETL Pipeline 

This project is an end-to-end ETL (Extract, Transform, Load) pipeline that fetches current weather data for Nairobi using the OpenWeather API, processes the data with Pandas, and stores it in a PostgreSQL database. The pipeline captures key weather metrics such as temperature (Kelvin), humidity, and weather description for further analysis or reporting.

---

##  Features

- Data Extraction: Fetches real-time current weather data for Nairobi from the OpenWeatherMap API using requests
- Data Transformation: Processes the raw JSON data into a structured format suitable for relational databases.
- Data Loading: Loads the tranformed data into a postgreSql database.
- Notebook-first development: For debugging


---

##  Technologies Used

- Python 3.8+
- Pandas: Data transformation.
- SQLAlchemy: Python SQL Toolkit and Object Relational Mapper (ORM) for database interactions.
- Psycopg2: PostgreSQL adapter for Python.
- OpenWeather API: Source of weather data.
- PostgreSQL: Relational database for storing weather data (hosted on Aiven). 
- Jupyter Notebook environment.

---
## Environment set upgit

```bash
##clone the repository
git clone https://github.com/Brian-m545/weather-data-ETL-Pipeline.git
cd weather-data-ETL-Pipeline

## Install Dependancies
```bash
pip install -r requirements.txt

##  Create a virtual environment:
``bash
python -m venv venv

```

###  Acknowledgments
- OpenWeatherMap: For providing the weather API.
- Aiven: For providing managed PostgreSQL database services.
- DBeaver: For the excellent database management tool.
