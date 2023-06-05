# Unreal-EXNO-01-Implementing-various-effects-in-materials
## Exp01 - Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

                                                                                     
## AIM:
To Implement various effects in a material such as emissive, roughness, and metallic properties in Unreal Engine
## Steps Required:
### Step-1:
Right-click in the content browser and choose material
### Step-2:
Rename the material and double-click to open it
### Step-3:
Right-click in the working space and search for constants
### Step-4:
In constant choose constant vector 4
### Step-5:
After this double click on the constant vector 4 and edit the color using the color picker
### Step-6:
After adjusting the color click okay and save it

### Step-7:
They join the output of the constant vector 4 to the base color
### Step-8:
Create a single constant using step 3 and adjust its value of it using detail pannel by adjusting the value
### Step-9:
And you can apply this constant value to metallic, roughness, emissive color etc...
### Step-10:
For emissive you need to multiply the constant vector 4 and constant and apply it to emissive color
### Step-11:
For creating walls and gate you need to create a material and import a png image .
### Step-12:
And use the png image as texture sample and connect the (rgb) of texture sample to the emmisive color & connect the alpha value of texture sample to the opacity
### Step-13:
The save it, go to the third person example map and create a plane or cube apply th material which you have created for the wall or gate



## Output:
## Basic-Color:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-01-Implementing-various-effects-in-materials/assets/94233064/099f4b71-b304-42a4-afa0-6b948fb533f1)

 
## Emmisive:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-01-Implementing-various-effects-in-materials/assets/94233064/9f35aa69-972d-4de2-b37e-e838e4d77730)

 
## Metallic:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-01-Implementing-various-effects-in-materials/assets/94233064/102950ae-a447-4ab2-ac49-2f6a33810c35)

 
## Roughness:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-01-Implementing-various-effects-in-materials/assets/94233064/871889cb-8dba-4341-a8f7-59326219714a)


 
## Result:
Thus, To Implementing various effects in material properties in Unreal Engine is implemented successfully.
