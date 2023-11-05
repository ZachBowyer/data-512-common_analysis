# data-512-common_analysis
Course project part 1 - Common Analysis sets the stage for the subsequent  
 assignments. In Part 1 you conduct a base analysis. All of the students in  
 the class will conduct the same analysis, but with a slightly different data subset.  

Specfically, I am assigned to look at Kansas, Leavenworth. 
(Population: 37081)
(County: Leavenworth)

# Research question:
What are the estimated smoke impacts on Leavenworth, Kansas for the last 60 years?

Answer: I came up with a simple formula to estimate the amout of smoke received by Leavenworth annually.


# Data sources:
```
1. Name:  
        Combined wildland fire datasets for the United States and certain territories,   
        1800s-Present (combined wildland fire polygons)    
   Description:  
        Combination of many smaller/incomplete United States fire datasets. "Encompasses  
        known wildfires and prescribed fires within the United States and certain territories."[1]  
   URL:  
        https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81    
   Schema/Info:     
        Wildland_Fire_Polygon_Metadata.xml - Additional dataset information
```
```
2. Name:  
        &emsp;
        &emsp;
   Description:  
        &emsp;
        &emsp;
   URL:  
        &emsp;
   Schema:   
        &emsp; 
```

# Description of all project directories and files

```
./Data/ - Directory of all relevant data files to this project. Most data is gitingored.   

Fire_Feature_Data.gdb - Wildland Fire polygons in ArcGIS Pro 2.8 Geodatabase format

```

```
./Src/ - Directory containing main project files and notebooks
```

```
./Archive/ - Collection of example files or files that are no longer needed
1. epa_air_quality_history_example.ipynb - Example of requesting data from the EPA AQS api. 
2. wildfire_geo_proximity_example.ipynb  
```

LICENSE - MIT LICENSE statement

README.md - Project documentation (This file)

# Commands
python -m ipykernel install --user --name=Data512Project


# References
1. https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81 
2. 