## Overview
This is a Dash-powered interactive web application that visualizes and analyzes the energy consumption of various sorting algorithms based on input size. The dashboard includes an ANOVA statistical analysis feature to compare performance differences.

## Features
- **Data Table:** Displays sorting algorithm energy consumption data.
- **Interactive Graphs:** Visualizes energy consumption across different algorithms.
- **ANOVA Analysis:** Statistical comparison of energy consumption across algorithms.
- **Generalized ANOVA Calculator:** Allows users to input custom data for statistical testing.
- **User-Friendly Interface:** Built using Dash and Plotly.

## Technologies Used
- Python 
- Dash (Plotly) 
- Pandas 
- SciPy (ANOVA Analysis) 

## Dataset
The application uses `energy_consumption.csv`, which contains the following columns:
- **Algorithm:** Name of the sorting algorithm.
- **Input_Size:** Size of the input (Small, Medium, Large, Extra Large).
- **Energy_Consumption:** Energy consumption measured for each algorithm.
- **CPU_Usage, Memory_Usage, Run_Time:** Additional performance metrics.

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Vedashree14/Sorting-Energy-Dashboard.git
   cd Sorting-Energy-Dashboard
   ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application:
   ```bash
    python app.py
   ```
4. Open your browser and go to:
   ```bash
    http://127.0.0.1:8050/
   ```
## Usage
1. Select an input size to view the energy consumption graph.
2. Use the ANOVA calculator to analyze statistical differences.
3. Enter custom values in the Generalized ANOVA section to perform an independent analysis.

<br>

<img width="1267" alt="Screenshot 2025-02-08 at 19 58 12" src="https://github.com/user-attachments/assets/783d3966-8296-4f78-990d-8d949134a335" />

<img width="1122" alt="Screenshot 2025-02-08 at 19 58 22" src="https://github.com/user-attachments/assets/38c5a5d1-4a77-4edb-91fa-aa6bac3d168e" />

<img width="1466" alt="Screenshot 2025-02-08 at 19 58 30" src="https://github.com/user-attachments/assets/df0043b6-de57-4075-9b07-cb301f4f4c59" />
