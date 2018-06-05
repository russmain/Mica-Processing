# Mica-Processing
  Code for processing multiple multispectral images captured from UAV platforms. This code is based off of the Micasense RedEdge image processing tutorial. 
For the original tutorial go here: https://micasense.github.io/imageprocessing/MicaSense%20Image%20Processing%20Tutorial%201.html. 
 This code is designed to correct multispectral photos captured with the Micasense RedEdge camera. The code corrects photos based on the reflectance from calibration panel, it also corrects for lens distortion. 
  Disclaimer: most of this code came from the tutorial, I simply made it into functions for processing large volumes of photos. I also included code to prevent metadata from being lost when the photos are being procesed. The two codes are for outputting the photos as a coloured graph or in '.tif' format. Examples for how to loop through the final calibration and rename the corrected output photos are provided at the end of each code.  
Coding was done using python in a Jupyter Notebook. 
