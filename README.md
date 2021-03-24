# Image_Segmentation_UNet_OxfordPets
This repository illustrates how to build a UNet for semantic image segmentation. This architecture is also a fully convolutional network and is similar to the model we just built in the previous repository. A key difference is the use of skip connections from the encoder to the decoder.  At the end of this lab, we will be able to use the UNet to output segmentation masks that shows which pixels of an input image are part of the background, foreground, and outline.

![image](https://user-images.githubusercontent.com/64538407/112272551-06598080-8c85-11eb-9784-aac0454ff2c0.png)

Here is the overall structure of UNet:

![image](https://user-images.githubusercontent.com/64538407/112272690-2f7a1100-8c85-11eb-89e9-f67de9731f3d.png)

Here is the encoder part:

![image](https://user-images.githubusercontent.com/64538407/112272744-3f91f080-8c85-11eb-93c7-27b183592015.png)

And here is the decoder part:

![image](https://user-images.githubusercontent.com/64538407/112272788-4caedf80-8c85-11eb-99a5-e60931e096f6.png)

After running the code for 10 epochs, here are the validation and the training loss:

![image](https://user-images.githubusercontent.com/64538407/112273019-8a136d00-8c85-11eb-82c5-a5892ff6cd07.png)



