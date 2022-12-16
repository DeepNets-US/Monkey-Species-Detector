# Monkey-Species-Detector

This is the "Monkey Classification | Big Transfer | Acc:  99%" notebook. This notebook contains the data visualization and model creation for monkey species data set. 
Both the notebook and the monkey species data set are created by me. Data Visualization includes : 

* Class Distribution 

![image](https://user-images.githubusercontent.com/118154709/208200553-90fba4ff-7785-46a9-999a-d670c52ebbab.png)

* Data Visualization

![image](https://user-images.githubusercontent.com/118154709/208200602-5dc7f973-bd0b-479b-b073-e103d34ad7c6.png)


The main attraction of the notebook is the **Big Transfer model**. From architecture perspective BiT is nothing but a 4x times Scaled version of ResNet152V2.
The main idea here is of Transfer Learning, this model is pre-trained on a Large Dataset, so it can be trained on sub-datasets or basically other small datasets and as the model is pre-trained on a Very large Dataset it is expected that it will perform extremely well on the small dataset. There are 3 variants of BiT :

* BiT-L : This is trained on Image Classification task of 300M Samples(This is Private).
* BiT-M : This is trained on Image Classification task of 14M Samples.
* BiT-S : This is trained on Image Classification task of 1.3M Samples.

Here is the learning curve of the transfer learning BiT model.

![image](https://user-images.githubusercontent.com/118154709/208200669-5871b26f-e11f-4fb1-a79e-9670cf377d1c.png)

The Model was able to obtain a robust performance, with the following accuracies :

* 95% Training Accuracy
* 94% Validation Accuracy
* 93% Testing Accuracy

---
**DeepNets**
