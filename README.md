# ASU-GIS-322
This repositoray contains the learning materials for GIS 322: Programming Principals II.
Designed by Ziqi Li (liziqi1992@gmail.com) and Wenwen Li (wenwen@asu.edu), School of Geographical Sciences and Urban Planning, Arizona State University.

Module 0: Welcome and Start Here
* Set up Your Programming Environment - Introduction to Google Colaboratory

Module 1: Review of Python Basics
* Data Types, Functions and Modules
* Conditions and Loop
* Review of Numpy for Basic Usage and File Read

Module 2: Spatial Features and Data Structure
* Vector Part 1
* Vector Part 2

Module 3: Geometry operations using Shapely
* Geometry Collection in Shapely
* Spatial Relationship
* Matplotlib Display Shapely Object

Module 4: Managing GIS Data in Python
* Reading and Writing Spatial Data
* Map Projections
* Creating a GeoDataFrame from Coordinates

Module 5 Geospatial Operations and Geoprocessing
* Geometric Operations
* Table Join and Spatial Join
* Geocoding

Module 6 - Advanced Geovisualization in Python
* Interactive Mapping with Bokeh
* Adding a Web Basemap using Folium

Module 7
* Final project



# How to modify GitHub Repoitory and Canvas of GIS 322

(1) Make repository changes.

(2) Change the hyper link of the “Open in Colab” button. Open a notebook (https://github.com/Yuanyuan-T/ASU-GIS-322-Summer-2021/blob/master/notebooks/5_3_Geocoding.ipynb), in “change” mode, find the below code block, change the domain from 'github.com' to 'githubtocolab.com' (ref: https://stackoverflow.com/questions/62596466/how-can-i-run-notebooks-of-a-github-project-in-google-colab). 

"source": [
        "<a href=\"https://github.com/Yuanyuan-T/ASU-GIS-322-Summer-21/blob/master/notebooks/5_3_Geocoding.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]


(3) Get the rendered page:
Copy the name of the GitHub repository (https://github.com/Yuanyuan-T/ASU-GIS-322-Summer-2021) in https://nbviewer.jupyter.org/.
*Notice that nbviewer has caching issue, it won’t change in time if you make changes on GitHub after you render any page in your repository. So the best practice is to ensure everything of the repo is good to go, then render this repo. One walk around is to rename your repo, and render it again. 

(4) Change the link to the rendered GitHub page:
<img width="800" alt="Raw HTML Editor" src="https://user-images.githubusercontent.com/43053656/125877494-ad993e99-c530-4c4e-96be-c9e9675b1348.png">

