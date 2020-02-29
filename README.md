# Pneumonia Classification Using CNN

If this repository helps you in anyway, show your love :heart: by putting a :star: on this project :v:

Dataset from [https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Layer Structure

```Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 160, 160, 16)      160       
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 160, 160, 16)      2320      
_________________________________________________________________
max_pooling2d (MaxPooling2D) (None, 80, 80, 16)        0         
_________________________________________________________________
separable_conv2d (SeparableC (None, 80, 80, 32)        688       
_________________________________________________________________
separable_conv2d_1 (Separabl (None, 80, 80, 32)        1344      
_________________________________________________________________
batch_normalization (BatchNo (None, 80, 80, 32)        128       
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 40, 40, 32)        0         
_________________________________________________________________
separable_conv2d_2 (Separabl (None, 40, 40, 64)        2400      
_________________________________________________________________
separable_conv2d_3 (Separabl (None, 40, 40, 64)        4736      
_________________________________________________________________
batch_normalization_1 (Batch (None, 40, 40, 64)        256       
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 20, 20, 64)        0         
_________________________________________________________________
separable_conv2d_4 (Separabl (None, 20, 20, 128)       8896      
_________________________________________________________________
separable_conv2d_5 (Separabl (None, 20, 20, 128)       17664     
_________________________________________________________________
batch_normalization_2 (Batch (None, 20, 20, 128)       512       
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 10, 10, 128)       0         
_________________________________________________________________
dropout (Dropout)            (None, 10, 10, 128)       0         
_________________________________________________________________
separable_conv2d_6 (Separabl (None, 10, 10, 256)       34176     
_________________________________________________________________
separable_conv2d_7 (Separabl (None, 10, 10, 256)       68096     
_________________________________________________________________
batch_normalization_3 (Batch (None, 10, 10, 256)       1024      
_________________________________________________________________
max_pooling2d_4 (MaxPooling2 (None, 5, 5, 256)         0         
_________________________________________________________________
dropout_1 (Dropout)          (None, 5, 5, 256)         0         
_________________________________________________________________
flatten (Flatten)            (None, 6400)              0         
_________________________________________________________________
dense (Dense)                (None, 512)               3277312   
_________________________________________________________________
dropout_2 (Dropout)          (None, 512)               0         
_________________________________________________________________
dense_1 (Dense)              (None, 128)               65664     
_________________________________________________________________
dropout_3 (Dropout)          (None, 128)               0         
_________________________________________________________________
dense_2 (Dense)              (None, 64)                8256      
_________________________________________________________________
dropout_4 (Dropout)          (None, 64)                0         
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 65        
=================================================================
Total params: 3,493,697
Trainable params: 3,492,737
Non-trainable params: 960```

## Contacts

If you want to keep updated with my latest articles and projects follow me on Medium. These are some of my contacts details:

1. [Personal Website](https://maftuhm.github.io/)
2. [Linkedin](https://in.linkedin.com/in/maftuhm)
3. [GitHub](https://github.com/maftuhm)
