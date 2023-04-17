# Weather in Seattle

## Description
  
This is a project that contains information and data about seattle weather. This project compares the precipitation in two cities, Seattle and St. Louis. The project will utilize data about the amount of rainfall for each day and use that to draw conclusions about what city has more rain and is considered a more "rainier" city.

## Requirements
For this project, the software that was used was google collab for compling and editing the files. The code that was used was written in .ipynb files which are a version of juypter notebooks that are a subset of python also known as a python notebook. The report was written in word and the .csv files that contain the data can be opened and viewed in excel.

## Data
There are two files in the project. One file seattle_rain.csv about rain in seattle. The other file is stl_rain.csv and this is about rain in St. Louis, MO. This data was collected from this source: https://github.com/brian-fischer/DATA-3320. The data from the linked source was collected from the NOAA National Centers for Environmental Information, an organization that collects data about environments and precipitation. We used their records of daily precipitation from Seattle and St. Louis (or other locations of interest) for the last 5 years (2018 - 2022) to draw conclusions which is where the linked github gathered the data from.

## Data Preparation
-The data was prepared by insepcting the data, removing any undesired data. The days that had no data for precipatation on a certain day was calculated by finding the mean of that day in other years. The data from St. Louis was cleaned to only include the data from 2018 and above and only from one satelite. The Seattle and St. Louis data was then combinded together to create one dataset. 
-The file in the dataset that does the data preparation is DATA_3320_Seattle_St_Louis_Data_Preparation.ipynb.

-The clean data file is clean_seattle_stl_weather.csv.

-The data was used from the clean_seattle_stl.csv to draw conclusions about what city has more rainy days and on the days that it rains, what city has harder rainy days such as more rainfall on those days.


## Author
The author of this notebook was Supreet Sandhu.
A link to her linkedIn: https://www.linkedin.com/in/supreet-sandhu/

## License
Members of the public are able to use and view the content of this project. They are able to use this notebook for their own work and education with citation given to the Author of this notebook.



