# Final Map Project 
Final mapping project for MAP 671
# Topographic Map of Aquidneck Island, Rhode Island (Final Project)

**Author:** Samuel Koontz  
**GitHub Username:** seko227    
**Date:** October 16 2025  

## Project Overview
This project presents a topographic map of Aquidneck Island, Rhode Island, United States of America, with significant Revolutionar War fortications marked. The purpose of this map is to appreciate the spatial strategic advantages that each position would have offered, particularly Butts Hill Fort, located on the highest point on the northern side of the island.
All elements of this project were compiled using **QGIS 3.40.11 “Bratislava.”**

## Data Sources
- **National Elevation dataset:** Copernicus GLO-30 (TIFF format)  
  - [USGS download](https://apps.nationalmap.gov/downloader/)

  **Fort Coordinate sources**   
  - Rhode Island Historical Society; Battle of Rhode Island Association, “Butts Hill Fort Restoration Project,” battleofrhodeisland.org (accessed 2025)
  - Newport Historical Society, “Green End Fort,” newporthistory.org/properties/green-end-fort; USGS Newport 7.5’ topographic quadrangle
  - Battle of Rhode Island Association, “Fortifications of Aquidneck Island,” battleofrhodeisland.org/fortifications
  - Rhode Island State Parks; Newport Historical Society; US Coast Survey Chart No. 1 (1776)
  - Battle of Rhode Island Association; John Murray, “Plan of the Fortifications on Rhode Island, 1778,” Library of Congress Map Division
  - Newport Parks Dept.; National Register of Historic Places Nomination Form, Miantonomi Memorial Park (1970)

## Methods
1. Imported Tiff rastor data into QGIS.  
2. Used Clip Raster by Extant : clip data to area encompassing Aquidneck Island at 1:5,000 scale.
3. Used Contour tool to make elevation contours within a 10 foot interval 
4. Used Field Calculator to make index contours for every 100 feet. Contour layer was chosen to be mint green to symbolyze the dense vegetation of the area and to contrast with black labelling. 
5. Added GPS points of Revolutionary War forts as shapefile layer.
6. Customized print layout, adding legend, north arrow authorship information.  
8. Exported the print map at two resolutions:  
   - **Web version:** 300 px width  
   - **High-resolution:** 2000 px width  

## Projection Information
- **Final Map CRS:** EPSG:4269 

## View the Map
- [View Web Map on GitHub Pages](https://seko227.github.io/Final-Map-Project/)  
- [Download High-Resolution Map (2000 px PNG)](images/Aquidneck Island Forts.png)

## Software
- QGIS 3.40.11 
 

## Reflection
Completing this project provided me with an understanding of how to integrate differant data types and display them within programs like QGIS. Previously, I had only done simple mapping projects that mainly displayed shapefiles. Now, I understand how to integrate those shapefiles to showcase their relationship with different data sets, such as elevation change as shown here.