# Artistic Style Transfer.

We are 
- Martí Baldi NIA 208238
- Cesc Bausà NIA 206059
- Marta Borrull NIA 206745

Here it is out final project of deep learning. 

The idea of this project is to take some pictures and by applying the style of a picture, transform them.

There are two documents of code, one for the AlexNet model and one for the VGG 19 model.
Then there are two more files:
  - Images, which it has the content and the sytle images ( in two separate files).
  - Results that have all the generated images.

In order to execute the code:
  - It is needed to change just the name of the pictures, to decide which transformation is wanted to be done.
  - The default parameters are:
    - the content layer is = ['conv_4']
    - the layers used for the style are  = ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5']
    - num_steps=300
    - style_weight=1000000
    - content_weight=1
