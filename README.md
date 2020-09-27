                        # Mask_Detector
***
## Transfer learning Using **VGG16 MODEL**
     - Implementation of Transfer Learning for training model:
            1. Only last later is set to trainable with top layer included.
            2. Model is trained for **10 EPOCHS**
            3. Optimizer used is **Adam** and Learning Rate is **0.001**
            4. Loss function used is **binary_crossentropy**

    - Details of Dataset:
            1. Dataset is classified into two category (with_mask and without_mask)
            2. No of Images in Dataset:
                       | with_mask | without_mask |
                       |---------- |------------- |
                       |**1915** | **1918** |
            3. Batch size for training and testing **30**
            4. Images are first preprocessed using voila-jones algorithm and resized to **(224,224)** to feed it into VGG16 model.

****
# WORKING DEMO
[![Video Description of project](https://youtu.be/XwXRfrNR-jo)](https://youtu.be/XwXRfrNR-jo)

****
## How to run the code?
- Download any available dataset and resize it to (224,224,3).
- After that execute **mask_detector_using_tl.ipynb** file.
- And then execute **detector_mask.ipynb** file.
