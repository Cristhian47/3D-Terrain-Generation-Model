# 3D Terrain Generation Using A Machine Learning Model

In this repository you will be find an explanation about some necessary concepts used in this model, additionally you will find some examples of uses of this model in the game development area.

3D terrain using heightmaps:

A terrain generation technique consists of pre-creating the terrain to be used in the game. However, before explaining this process, it must be clear that it is a height map.

A heightmap is a NURBS surface or mesh (mathematical representations of 3D geometry capable of accurately describing any shape) based on the grayscale values of the colors of an image file. An example of this are the following height maps.

![Pereira And Dosquebradas](https://user-images.githubusercontent.com/75464976/233254521-d450d24a-0263-4576-9752-ef3ab0f91bf3.png)
Image extracted from the website https://heightmap.skydark.pl/

The previous image is an example of a Heightmap. Were black pixels are the minimum height and white pixels are maximum height, the grayscales are intermediate values of height.

Using this image to get a 3D terrain using, in this case Unity, We get that the 3D terrain is the next one:

![TerrainPereira](https://user-images.githubusercontent.com/75464976/233256668-e543f6f8-dabf-49b8-b2f0-25ec79055cfb.PNG)

Creating Game Objects over the terrain:

To create some game objects over the terrain is necessary to have a object pool with all the prefabricated elements that will be used in the videogame, later an algorithm is executed, check the heightmap image pixels and indicates what object will be created in which coordenate


References:

D. M. D. Carli, F. Bevilacqua, C. Tadeu Pozzer and M. C. d'Ornellas, "A Survey of Procedural Content Generation Techniques Suitable to Game Development," 2011 Brazilian Symposium on Games and Digital Entertainment, Salvador, Brazil, 2011, pp. 26-35, doi: 10.1109/SBGAMES.2011.15.

Dan Meng, X. Cai, Zhitong Su and Jinhong Li, "Photorealistic terrain generation method based on fractal geometry theory and procedural texture," 2009 2nd IEEE International Conference on Computer Science and Information Technology, Beijing, China, 2009, pp. 341-344, doi: 10.1109/ICCSIT.2009.5234644.

Y. Zhang, G. Zhang and X. Huang, "A Survey of Procedural Content Generation for Games," 2022 International Conference on Culture-Oriented Science and Technology (CoST), Lanzhou, China, 2022, pp. 186-190, doi: 10.1109/CoST57098.2022.00046.

D. Demergis, "Comparative Analysis of Machine Learning Techniques for Island Heightmap Generation," 2021 International Joint Conference on Neural Networks (IJCNN), Shenzhen, China, 2021, pp. 1-8, doi: 10.1109/IJCNN52387.2021.9533580.

