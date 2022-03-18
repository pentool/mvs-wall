# MagicaVoxel Wall Shader

This shader creates various wall-like structures. It has three modes to create walls, lines, or points. You can adjust the model box X/Y/Z size to limit the respective axis size to create longer, wider, narrower, or taller structures.

You can use this shader in Voxel Shader Mode as well, which allows you to modify the paramters and adjust the model cage in realtime.

To install, download "mvs-wall.txt" and place it into your "MagicaVoxel > shader > custom" folder.

## Parameters

### Type
Values: 1 - 3  
Type of structure to generate. 1 - walls, 2 - lines, 3 - points. In type 3 (point) mode, the x/y/z axes settings are ignored.

### Spacing
Values: 0 - 255  
Spacing between voxels.

### Thickness
Values: 1 - 255  
Adjust the thickness of the generated structure.

### X/Y/Z Axis
Values: 0, 1  
Create voxels on the selected axes. You can select a single or multiple axes. When the value is set to 0, that axis will be ignored.

### X/Y/Z Offset
Values: -255 - 255  
Offset the structure left/right or up/down by this many voxels to generate symmetrical surfaces.

## Examples
Look at the parameter values and model box size on the screenshots to recreate the structure. (Click image for larger version.)

Default "wall".

<img width="450" alt="1" src="https://user-images.githubusercontent.com/1972916/157359038-6c4f380c-1509-47dc-9dcf-21c6bfb8c201.png">

Default "line".

<img width="450" alt="2" src="https://user-images.githubusercontent.com/1972916/157359366-f753aa46-4232-474b-bebe-2b7dca3ed3b6.png">

Default "point".

<img width="450" alt="3" src="https://user-images.githubusercontent.com/1972916/157359442-26e50a2b-5e8a-41d5-99db-d60e42baa0f2.png">

Variations on "wall".

<img width="450" alt="1 1" src="https://user-images.githubusercontent.com/1972916/157359774-36111643-018f-4893-a747-9de7996f1266.png">

<img width="450" alt="1 1" src="https://user-images.githubusercontent.com/1972916/159081594-f5410926-c545-4c06-b259-7f3e0707b21b.png">

<img width="450" alt="1 1" src="https://user-images.githubusercontent.com/1972916/159081635-6d39ed7f-4d17-4cfa-b344-5f5dbf1aa5fa.png">

<img width="450" alt="1 2" src="https://user-images.githubusercontent.com/1972916/157359807-ba53e9f9-32b2-49af-8588-0ca108d54f04.png">

<img width="450" alt="1 3" src="https://user-images.githubusercontent.com/1972916/157359845-68fab888-dc17-4858-b1c7-00d308b11bb8.png">

<img width="450" alt="1 4" src="https://user-images.githubusercontent.com/1972916/157359876-fc68cf88-bf2f-4928-8add-b43d293405ea.png">

<img width="450" alt="1 5" src="https://user-images.githubusercontent.com/1972916/157359892-948862f5-cee8-423b-8ed3-4e0fcd8c0bb1.png">

<img width="450" alt="1 6" src="https://user-images.githubusercontent.com/1972916/157359910-10827382-0470-461b-b54c-1d6e97e29c3b.png">

Variations on "line".

<img width="450" alt="2 1" src="https://user-images.githubusercontent.com/1972916/157360092-520cf105-7f9a-405f-a936-ef0eb97eb046.png">

Using the Move Tool we can move the voxels up/down on the Z-axis to instantly create a fence.

<img width="450" alt="2 2" src="https://user-images.githubusercontent.com/1972916/157360122-5cbf144f-7f03-4a0c-afc0-e0e8c0fc7cea.png">

Variation on "point".

<img width="450" alt="3 1" src="https://user-images.githubusercontent.com/1972916/157360301-18e77aef-50d6-42f4-bd3f-486a63506a5c.png">
