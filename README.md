# tensorflow
A Neural Algorithm of Artistic Style
model from article A Neural Algorithm of Artistic Style by Leon A. Gatys, Alexander S. Ecker, Matthias Bethge

What is neural style transfer?

Neural style transfer is an optimization technique used to take three images, a content image, a style reference image (such as an artwork by a famous painter), and the input image you want to style -- and blend them together such that the input image is transformed to look like the content image, but “painted” in the style of the style image.

For example, let's take this images:

This 2 dogs

iz-strazhy-tora-19831.jpeg

and this stained glass

StainedGlass0.jpeg

We will follow the this steps to perform style transfer:

Visualize date
Basic Preprocessing/preparing our data
Set up loss functions
Create model
Optimize for loss function
