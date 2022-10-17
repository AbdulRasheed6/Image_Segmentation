# Image_Segmentation

#### With rise and advancements  of computer vision models we are able to build computer vision models that can detect objects, determine their shape, and predict the direction the object would go in .Though various computer vision teechniques like object detection, image localisation etc have performed excellently well but have come off short in some scenarios. But with the advents image segmentation techniques we have been able to overcome such  limitations in various  aspect of computer vision  like medical imaging, self-driving cars,  satelite imaging and so on .

##### U-Net, named for its U-shape, was originally created in 2015 for tumor detection, but in the years since has become a very popular choice for other semantic segmentation tasks. 

U-Net builds on a previous architecture called the Fully Convolutional Network, or FCN, which replaces the dense layers found in a typical CNN with a transposed convolution layer that upsamples the feature map back to the size of the original input image, while preserving the spatial information. This is necessary because the dense layers destroy spatial information (the "where" of the image), which is an essential part of image segmentation tasks. An added bonus of using transpose convolutions is that the input size no longer needs to be fixed, as it does when dense layers are used. 

Unfortunately, the final feature layer of the FCN suffers from information loss due to downsampling too much. It then becomes difficult to upsample after so much information has been lost, causing an output that looks rough. 

