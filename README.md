# Mica-Processing
Code for processing multiple multispectral images, based off of the Micasense RedEdge image processing tutorial. 
For the original tutorial go here: https://micasense.github.io/imageprocessing/MicaSense%20Image%20Processing%20Tutorial%201.html
This code is designed to take multispectral photos captured with the Micasense RedEdge camera from UAV platforms and correct their reflectance as well as correct lens distortion. 
Disclaimer: most of this code came from the tutorial, I simply made it into functions for processing large volumes of photos. I also included code to prevent lat, long, and alt metadata from being lost. You can output photos as a coloured graph or just as a tif. Examples for how to loop through the final calibration and rename the corrected output are provided at the end of each code. 
Coding was done using python in a Jupyter Notebook. 
