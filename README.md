# 3D Terrain Generation Using A Machine Learning Model

A terrain generation technique consists of pre-creating the terrain to be used in the game. However, before explaining this process, it must be clear that it is a height map.

A heightmap is a NURBS surface or mesh (mathematical representations of 3D geometry capable of accurately describing any shape) based on the grayscale values of the colors of an image file. An example of this are the following height maps.

![Pereira And Dosquebradas](https://user-images.githubusercontent.com/75464976/233254521-d450d24a-0263-4576-9752-ef3ab0f91bf3.png)
Image extracted from the website https://heightmap.skydark.pl/

The previous image is an example of a Heightmap. Were black pixels are the minimum height and white pixels are maximum height, the grayscales are intermediate values of height.

Using this image to get a 3D terrain using, in this case Unity, We get that the 3D terrain is the next one:

