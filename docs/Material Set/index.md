# Material Set

## Overview
![Alt text](<../assets/Material Set/overview.jpg>)

The Material Set functions to manage all materials of an object. We can add or remove a material from the object's material slot here.

## Status
Importantly, it will inform us about the status of a material, indicating whether it has a Plx Shader or not. Philogix PBR Painter operates on Plx Shader, so only materials with Plx Shader can work with the material layers inside that material.

The status of the material will be indicated by a checkmark icon or a warning icon as shown below:
![Alt text](<../assets/Material Set/status.jpg>)

## Plx Function
At the bottom of the Material Set, there are functions related to working with Plx Shader:

- New Plx Shader: This button adds a Plx Shader to a material; it is only displayed when a material does not have a Plx Shader.<br>
![Alt text](<../assets/Material Set/new.jpg>)

- Fix Plx Shader: This button is responsible for finding and fixing errors within the Plx Shader; it is only displayed when the selected material contains a Plx Shader.<br>
![Alt text](<../assets/Material Set/fix.jpg>)

- Duplicated Material: It duplicates a material layer with Plx Shader.<br>
![Alt text](<../assets/Material Set/duplicated.jpg>)

- Remove Plx Shader: This function removes the Plx Shader and related data from a material.<br>
![Alt text](<../assets/Material Set/remove.jpg>)