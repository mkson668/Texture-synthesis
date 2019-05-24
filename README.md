# Texture-synthesis
Texture synthesis based on Efros and Leung approach

## Running the program 

Get an image of your choice and change the variable name "imname" at line 90 to it, then run 

> python polyselect.py <br/>

this will allow you to indicate the region you want to synthesize on the image as well as the texture
you want to use for synthesis. They will be stored in files named fill_region.pkl and texture_region.pkl. 
Then perform the synthesis using the following

> python holefill.py <br/>

This might take up to several minutes depending on how big the region you selected

