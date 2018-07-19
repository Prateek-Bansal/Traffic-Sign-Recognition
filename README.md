
### Overview

This is the implementation of Traffic Sign Recognition Project deep neural networks and convolutional neural networks to classify traffic signs.
The model is trained, visualized and explored for better understanding of the pictorial data of traffic signs from natural images by using the [Traffic Sign Dataset]
(https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip).

 Final CNN Architecture :

 Layer (type)                 Output Shape              Param #   
 =================================================================
 conv2d_1 (Conv2D)            (None, 28, 28, 32)        2432      
 activation_1 (Activation)    (None, 28, 28, 32)        0         
 conv2d_2 (Conv2D)            (None, 24, 24, 32)        25632     
 activation_2 (Activation)    (None, 24, 24, 32)        0         
 max_pooling2d_1 (MaxPooling2 (None, 12, 12, 32)        0         
 conv2d_3 (Conv2D)            (None, 8, 8, 64)          51264     
 activation_3 (Activation)    (None, 8, 8, 64)          0         
 conv2d_4 (Conv2D)            (None, 4, 4, 64)          102464    
 activation_4 (Activation)    (None, 4, 4, 64)          0         
 max_pooling2d_2 (MaxPooling2 (None, 2, 2, 64)          0         
 dropout_1 (Dropout)          (None, 2, 2, 64)          0         
 flatten_1 (Flatten)          (None, 256)               0         
 dense_1 (Dense)              (None, 1024)              263168    
 activation_5 (Activation)    (None, 1024)              0         
 dropout_2 (Dropout)          (None, 1024)              0         
 dense_2 (Dense)              (None, 43)                44075     
 activation_6 (Activation)    (None, 43)                0     


### Dataset
 That is a pickled dataset in which we've already resized the images to 32x32.

