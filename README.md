## Lab 2 Data Pulling and QAQC

This repository contains several notebooks to perform the proccesses of downloading data, cleaning it, performing QAQC, and pushing it to a cloud geodatabase. These datasets include elevation, landcover, temperature, road lines, and sports schedules.
### Notebooks

1. **Sports Schedule Processing Notebook**
   - This notebook pulls sports schedules from gophersports.com, formats the data, and stores it in a csv. 

2. **Elevation Data QAQC Notebook**
   - This notebook retrieves Minnesota elevation data from the Minnesota Geospatial Commons, performs quality assurance and quality control checks, and ensures data integrity.

3. **Land Cover Data QAQC Notebook**
   - This notebook fetches Minnesota land cover data from the Minnesota Geospatial Commonsm conducts quality assurance and quality control procedures, and validates the accuracy of the data.

4. **Temperature Data QAQC Notebook**
   - This notebook gathers Minnesota temperature data from the NOAA, conducts QAQC analysis to identify anomalies or inconsistencies, and ensures data reliability.

5. **Traffic Scenario Road Line Generation Notebook**
   - This notebook generates road lines for scenarios with and without traffic during sporting events, aiding in traffic management and planning. This notebook utilizes the ESRI Network.

6. **Cloud Geodatabase Data Pushing Notebook**
   - This notebook pushes all processed data, including sports schedules, elevation, land cover, temperature, and road lines, into a local and cloud geodatabase for storage and accessibility.

### Requirements

- Python 3.x
- Jupyter Notebook
- arcpy
-
- Relevant Python libraries for data processing, geospatial analysis, and database interaction

### Usage

1. Clone or download this repository.
2. Ensure you have the necessary dependencies installed by running `pip install -r requirements.txt`.
3. Open Jupyter Notebook and navigate to the directory containing the notebooks.
4. Open the desired notebook and execute the cells to perform the specified data processing or analysis tasks.

### Note

- Each notebook contains detailed instructions and explanations of the data processing steps.
- Make sure to handle sensitive data securely, especially when pushing data into a cloud geodatabase.
- Customize the notebooks as needed to adapt to changes in data sources or processing requirements.

### Contributors

- [Your Name or Organization Name]

### License

This repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.

If you have any questions, issues, or suggestions, please feel free to reach out to the repository owner. Thank you for using our repository!