<snippet>
  
# Hologram Pyramid on Unity

Package to display a 3d model on a 3 side hologram on Unity.

![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/dragon_front.jpeg?raw=true)

## Getting Started

These instructions will show you how easy it is to use this package.

### Prerequisities

Download the .unitypackage file.

### Installation

1. Drag and drop the "Hologram Pyramid" from the Prefab folder.
2. Adjust front, left and right cameras to display your model as you prefer.
3. No need third step

## Architecture

![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/architecture.png?raw=true)

* The system has 3 different cameras (front, left and right).
![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/three_cameras.png?raw=true)


* Cameras are displayed in associated target texture.
![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/target_texture.png?raw=true)


* Target Texture are dispatched on a canvas containing 3 displays. Each display has the target texture as source.
![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/display.png?raw=true)


* If it doesn't fit to your physical hologram, you can adjust them by moving LeftDisp, RightDisp or FrontDisp.
![alt tag](https://github.com/Jakeur/hologram_pyramid/blob/master/images/fit_to_screen.png?raw=true)

## To go Further

* Replace Pikachu with any object you want.
* Attach "Cameras" part to a moving object.

## Contributing

You can use and modify it but you have to quote the original source.

## Authors

* Developer : Rodolphe Asséré
* Extracted and reworked from a project with : Thibault Bougerolles, Antoine Gazagne, Benjamin Roux and Alexis Laurent

## External resources

* [Pikachu 3D model]( https://github.com/hieuqdo/cs583pokemonfighter/blob/master/3D%20Game/3D%20Game/3D%20GameContent/Models/Pikachu.FBX)

## Any Question ?

Feel free to contact me at [rodolphe1.assere@epitech.eu](mailto:rodolphe1.assere@epitech.eu).

</snippet>
