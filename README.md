# Texture-synthesis
A non-parametric texture synthesis implementation based on Efros and Leung's approach. More details can be found at https://people.eecs.berkeley.edu/~efros/research/EfrosLeung.html

## Example

Suppose we have the following image: 
<br/>
<br/>
![Example](https://github.com/mkson668/Texture-synthesis/blob/master/images/donkey.jpg)

Select location to fill along with the texture to use for the fill:
<br/>
<br/>
![SelectFill](https://github.com/mkson668/Texture-synthesis/blob/master/images/donkey2.jpg)

Filled image:
<br/>
<br/>
![Result](https://github.com/mkson668/Texture-synthesis/blob/master/images/results.jpg)

## Running the program 

Get an image of your choice and change the variable name "imname" at line 90 to it, then run 

> python polyselect.py <br/>

This will prompt you to indicate the region you want to synthesize on the image as well as the texture
you want to use for synthesis. They will be stored in files named fill_region.pkl and texture_region.pkl. 
Then perform the synthesis using the following command

> python holefill.py <br/>

This might take up to several minutes depending on how big the region you selected

