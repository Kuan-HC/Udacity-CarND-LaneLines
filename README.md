# Udacity-CarND-LaneLines
<img src="img/cover_img.gif" width = "800"/>  
This project was developed on windows 10 with Anaconda, jupyter notebook installed.  

## Dependencies  
* matplotlib  
* opencv

## Image Process Pipeline
<img src="img/Pipeline_1.JPG" width = "900"/>  
<img src="img/pipeline_2.JPG" width = "450"/>  

## Line Extrapolation  
<img src="img/non_e.gif" width = "400"/> <img src="img/extrp.gif" width = "400"/>
<img src="img/Pipi_Extrap.JPG" width = "400"/>

## Shortcoming  
While extrapolating lines, only slope are considered as threshold to
categorized points set into left or right group. Which means the outputs can be
sever influence by road signs, cars ahead and split lane lines or any objects
with edges can pass Hough transformation criteria.
