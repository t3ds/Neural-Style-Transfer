#Neural-Style-Transfer

Current Attempt at Neural Style Transfer using Tensorflow.

Trying a couple of things with it, namely:

1. Variable weights to give different importance to layers

2. Layer selection

3. Using Image Interpolation to slowly introduce the stlye image and its contents into the training in order to preserve higher level intericate features of the content image

4. Eperimenting resizing style image to the same dimensions as the content image.

Below is an example output:

<div width=600 height = 500 align = 'center'>
  
  <div width = 200>
    Original Image<br>
    <img src="https://github.com/t3ds/Neural-Style-Transfer/blob/main/Green_Sea_Turtle_grazing_seagrass.jpg" alt="Original Image" width="400" height="400">
  </div>

<div width = 200>
<p>Style Image<p><br>
<img src="https://github.com/t3ds/Neural-Style-Transfer/blob/main/anime_img_2.jpg" alt="Style Image" width="400" height="400">
</div>
  
<div width =200>
<p>Output Image<p><br>
<img src="https://github.com/t3ds/Neural-Style-Transfer/blob/main/style_transfer_1.png" alt="Output Image" width="400" height="400">
  
</div>
</div>
