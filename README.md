# Computer Graphics Final Project
## Sasha Fomina and Queenie Xiang Period 4

### **New Implementations:**
* Lighting techniques! Users can now specify what kind of lighting they want by using constants. Users can now also have light from multiple light sources. 
* Two new shapes: cone and pyramid! 

### **New MDL Commands** ###
* **light lightsource_name r g b x y z** -- takes in a str, int, int, int, int, int, int. First three ints specify the light's rgb values and the last three ints specify the location of the light source

* **constants name kar kdr ksr kag kdg ksg kab kdb ksb** -- saves a set of lighting components in the symbol table under name. It goes in the order of ambient red, diffuse red, specular red, ambient green, diffuse green, specular green, ambient blue, diffuse blue, specular blue

* **cone x y z radius height** -- creates a cone at x y z location with specified radius and height

* **pyramid x y z height width** -- creates a pyramid at x y z location with specified height and width

