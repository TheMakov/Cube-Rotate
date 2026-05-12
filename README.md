# 3D-Wireframe Rendering engine
A program that is able to rotate any 3D object using C# and Project it onto a 2D canvas using the WPF framework
# How it works
1. we define vertecies, their location and which vertecies are connected to eachother
2. Each time the user makes an Input the Vertecies are transformed using a Rotationmatrix in the according direcation
3. We project the all the edges onto a 2D space and cull the vertecies that shouldnt be visible
# Structure 
* cubeWPF handles alle definitions, inputs and calls makes calls to the library
* PLP.Engine3D deals with all the transformations and culling
# Requirements
* .Net 10.0 SDK
