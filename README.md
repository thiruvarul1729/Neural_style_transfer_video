# Neural_style_transfer_video

  -The objective was to first implement Neural style transfer for an image with the appropriate hyperparameters, then use it to on videos and change style of a particular content video according to the style image.
  
  -I used VGG-19 a 19 layered pretrained model and its weights for implementing the neural style transfer.
  
  -This model has already been trained on the very large ImageNet database, and has learned to recognize a variety of low level features (at the shallower layers) and high level features (at the deeper layers).
  
  -For incoporating style we use these layers{'block1_conv1','block2_conv1',0.8),'block3_conv1','block4_conv1','block5_conv1'},
and 'block5_conv4' for content layer.

  -After doing it for an image,we just use the function on the required frames of the video with the frame rate of our choice and computational cost.
