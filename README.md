# IoT Sensor Data Analysis with Spark SQL

This project analyzes IoT sensor data using Spark SQL with PySpark, demonstrating loading, exploration, filtering, aggregation, time-based analysis, window functions, and pivot table creation.

---

## Tasks Overview

- **Task 1: Load & Basic Exploration**
- **Task 2: Filtering & Simple Aggregations**
- **Task 3: Time-Based Analysis**
- **Task 4: Ranking Sensors by Average Temperature**
- **Task 5: Pivoting Data and Interpretation**

Each task produces CSV outputs (`taskX_output.csv`).

---

## Prerequisites

- **Apache Spark** (version 2.x or 3.x recommended)
- **Python 3.x** with PySpark installed
- **IoT sensor data CSV** (`sensor_data.csv`) placed in the working directory

---

## How to Run the Tasks

1. **Navigate to your working directory**:

```bash
cd /path/to/your/directory
```

2. Execute the Spark script:
```bash
spark-submit spark_iot_analysis.py
```

Upon completion, the script generates these output files:

task1_output.csv

task2_output.csv

task3_output.csv

task4_output.csv

task5_output.csv

