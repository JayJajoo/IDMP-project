# IDMP-Project  
**Smart Home Sensor Data: Anomaly Detection and Activity Classification with Data Management and Visualization**  

---

## Table of Contents  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Data Outputs](#data-outputs)  
4. [Features](#features)  
5. [Installation](#installation)  
6. [Usage](#usage)  
7. [Project Structure](#project-structure)  
8. [Technologies Used](#technologies-used)  
9. [Contributing](#contributing)  
10. [License](#license)  

---

## Overview  
This project focuses on analyzing smart home sensor data to detect anomalies and classify activities. It incorporates efficient data management techniques and visualizations to provide actionable insights.  

---

## Dataset  
The dataset is stored in the `ARAS` folder.  

- **Source:** [ARAS Dataset](http://aras.cmpe.boun.edu.tr/download.php)  
- **Details:**  
  - Data collected from two houses (House A and House B).  
  - One month (30 days) of sensor readings.  
  - Includes data on residents’ activities and home environment.  

---

## Data Outputs  
The final outputs are present in the pipeline folder under respective houses.
All other intermediate processed outputs, including identified anomalies, will be saved in the `ARAS` folder. (It's not present in the repo, you need to run the files manually) 

---

## Features  
- **Anomaly Detection:** Identifies irregularities in sensor readings.  
- **Activity Classification Pieline:** Classifies activities based on sensor data.  
- **Data Visualization:** Provides meaningful visual insights.  
- **Data Management:** Organizes and preprocesses raw data for analysis.  

---

## Installation

- Clone the repository:
- git clone https://github.com/JayJajoo/IDMP-project.git
- cd IDMP-project
- Install required dependencies:
- pip install -r requirements.txt
- Ensure Python 3.8+ is installed.

---

## Usage

Test our anomaly detection pipeline you just need to run respective house pipeline files with some example scenarios.
You can create your scenarios and test them by just passing a new array to our existing array according to the expected input (20 sensor binary values, Both Resident Activities, Hour, Day Of Week, Week) = 25 input values for each scenario

---

## Project Structure
IDMP-project/  
├── ARAS/                # Dataset and data outputs  
├── scripts/             # Core Python scripts for analysis  
├── outputs/             # Generated reports and visualizations  
├── requirements.txt     # List of dependencies  
├── .gitignore           # Files to be ignored by Git  
├── README.md            # Project documentation  
└── LICENSE              # License information  

---

## Technologies Used

Programming Language: Python 3.8+

Libraries:

Pandas: Data manipulation and preprocessing.

NumPy: Numerical computations.

Matplotlib & Seaborn: Data visualization.

Scikit-learn: Machine learning and data analysis.

PyTorch: For model development.


