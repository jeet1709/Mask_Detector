# Mask_Detector
***
## Transfer learning Using VGG16 MODEL
#### Implementation of Transfer Learning for training model:
- Only last later is set to trainable with top layer included.
- Model is trained for **10 EPOCHS**
- Optimizer used is **Adam** and Learning Rate is **0.001**
- Loss function used is **binary_crossentropy**

#### Details of Dataset:
- Dataset is classified into two category (with_mask and without_mask)
- No of Images in Dataset:

|with_mask |without_mask |
|--------- |------------ |
|1915      |1918         |

- Batch size for training and testing **30**
- Images are first preprocessed using voila-jones algorithm and resized to **(224,224)** to feed it into VGG16 model.

****
# WORKING DEMO

[![Watch the video](https://i9.ytimg.com/vi/XwXRfrNR-jo/mq2.jpg?sqp=CKCQwvsF&rs=AOn4CLCVT0GKvNOZCtr2PPmVw11ep0RBxw)](https://youtu.be/XwXRfrNR-jo)

****

## How to run the code?
- Download any available dataset and resize it to (224,224,3).
- After that execute **mask_detector_using_tl.ipynb** file.
- And then execute **detector_mask.ipynb** file.
