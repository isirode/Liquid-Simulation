# Liquid Effect :ocean:

Fork of https://github.com/ivuecode/Liquid-Simulation.

An implemntation of liquid simulation effect in Unity.  

This project uses blur shaders along with 2D rigidbody sprites to create the illusion of a liquid body. Render textures and material instancing are methods also used to achieve this inexpensive fluid motion look.

## Preview :eyes:
![gif demo](https://i.imgur.com/4WCtDzh.gif)  

## Getting Started :page_with_curl:
Clone or download this repository and open the project with your favourite flavour of Unity.  
_This project was built with Unity 2021.3_

## Importing the project
You can add this package as a git url : "https://github.com/isirode/Liquid-Simulation.git?path=/Assets/Isirode/Liquid-Simulation#0.0.3". The project will be added to your "Packages" folder, the scenes will be read-only, if you want to open them, just copy them in your Assets folder and they will be usable.

You can also download the .unitypackage of the version you want, here for instance https://github.com/isirode/Liquid-Simulation/releases/tag/0.0.3 and add it manually to your project. This should import the project in your Assets folder.

## Known issues

The project is not currently compatible with URP or HDRP, built-in render pipeline only.

## Optimizations :pencil2:
There are a few points to consider when using this application:
* Using thousands of rigidbodys is very taxing. This effect should not be used to recreate the ocean. For a simple motion graphic effect such as the example gif, won't cause you any problems at all.

* Recreating this project with the new Unity ECS or Job System will drastically increase particle count.

## Contributing :muscle:
Looking to contribute something to this project? **Here's how you can help.**  
If you believe something needs to be immediately fixed please open an issue and document the problem. Fork this project and create a pull request with your solution to the problem. Thank you.  

[VueCode YouTube](https://www.youtube.com/channel/UCtP-1zQ2g_jpgYvvBqkWltA)  
[VueCode Twitter](https://twitter.com/VueCode/)  
[VueCode Discord](https://discord.gg/qWpEtR3)

