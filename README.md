# Predictive Traffic Modeling

This repository contains the final project for GIS 5572, predictive traffic modeling based on University of Minnesota sporting events. The project aims to predict traffic patterns using event data from the University of Minnesota's sports events, traffic data from ESRI, and machine learning models.

## Requirements

To run this project, you will need:

- Python 3.x
- [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)
- [ArcGIS Online](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview)
- [Google Cloud Run](https://cloud.google.com/run/)
- [Flask](https://flask.palletsprojects.com/)
- [GitHub](https://github.com/)

## Repository Structure

The repository consists of several parts, each with a specific purpose:

1. **Get Sport Code Notebook**: 
    - Retrieves and cleans information for sports played at the University of Minnesota.
    - Prepares the data for use in subsequent analyses.

2. **Roads Loop Notebook**:
    - Processes traffic data for each event in the  sport list and produces a shapefile.
    - Get initial traffic data needed for machine learning analysis.

3. **Data Cleaning Notebooks**:
    - Convert traffic line data into CSV format.
    - Merges traffic segments with sporting event data. 

4. **Machine Learning Notebooks**:
    - Input sporting event information and road segment information into a linear regression training model.
    - Produces traffic predictions based on three different models.
    - Inputs into geodatabase for use in ArcGIS Online. 
