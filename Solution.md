1. Are the results as expected? Why or why not?
Expected Results: Transfer learning with fine-tuning should outperform other models due to pre-trained weights capturing general features. Data augmentation is expected to improve generalization for the smaller dataset.
Reasons for Deviations: Results may deviate due to:
Insufficient training epochs.
Overfitting in larger VGG variants without augmentation.
Poor quality or ambiguity in the dataset.

2. Does data augmentation help? Why or why not?
Data augmentation introduces variability in training data (e.g., flips, rotations, brightness changes), improving generalization and reducing overfitting, especially for small datasets.

3. Does it matter how many epochs you fine-tune the model? Why or why not?
Fewer epochs may not allow the model to adapt to the new dataset fully.
Too many epochs risk overfitting, especially for smaller datasets.

4. Are there any particular images that the model is confused about? Why or why not?
Confusions: Likely for images that Share overlapping features between classes (e.g., similar colors, shapes).
and  low-quality, noisy, or contain backgrounds unrelated to the object.


#
mlp_vgg/1
![mlp_vgg/1](images\images\mlp_vgg\1.png "mlp_vgg/1")
mlp_vgg/2
![Alt text](images\images\mlp_vgg\2.png "mlp_vgg/2")
mlp_vgg/3
![Alt text](images\images\mlp_vgg\3.png "mlp_vgg/3")
mlp_vgg/4
![Alt text](images\images\mlp_vgg\4.png "mlp_vgg/4")
mlp_vgg/image
![Alt text](images\images\mlp_vgg\image.png "mlp_vgg/image")

vgg_onlymlp\1
![Alt text](images\images\vgg_onlymlp\1.png "mlp_vgg/1")
vgg_onlymlp\2
![Alt text](images\images\vgg_onlymlp\2.png "mlp_vgg/1")
vgg_onlymlp\3
![Alt text](images\images\vgg_onlymlp\3.png "mlp_vgg/1")
vgg_onlymlp\4
![Alt text](images\images\vgg_onlymlp\4.png "mlp_vgg/1")
vgg_onlymlp\image
![Alt text](images\images\vgg_onlymlp\image.png "mlp_vgg/1")

vgg1\image1
![Alt text](images\images\vgg1\image1.png "mlp_vgg/1")
vgg1\image2
![Alt text](images\images\vgg1\image2.png "mlp_vgg/1")
vgg1\image3
![Alt text](images\images\vgg1\image3.png "mlp_vgg/1")
vgg1\image4
![Alt text](images\images\vgg1\image4.png "mlp_vgg/1")
vgg1\image
![Alt text](images\images\vgg1\image.png "mlp_vgg/1")

vgg3_withau\1
![Alt text](images\images\vgg3_withau\1.png "mlp_vgg/1")
vgg3_withau\2
![Alt text](images\images\vgg3_withau\2.png "mlp_vgg/1")
vgg3_withau\3
![Alt text](images\images\vgg3_withau\3.png "mlp_vgg/1")
vgg3_withau\4
![Alt text](images\images\vgg3_withau\4.png "mlp_vgg/1")
vgg3_withau\5
![Alt text](images\images\vgg3_withau\5.png "mlp_vgg/1")

vgg3_withnoau\image1
![Alt text](images\images\vgg3_withnoau\image1.png "mlp_vgg/1")
vgg3_withnoau\image2
![Alt text](images\images\vgg3_withnoau\image2.png "mlp_vgg/1")
vgg3_withnoau\image3
![Alt text](images\images\vgg3_withnoau\image3.png "mlp_vgg/1")
vgg3_withnoau\image4
![Alt text](images\images\vgg3_withnoau\image4.png "mlp_vgg/1")
vgg3_withnoau\image
![Alt text](images\images\vgg3_withnoau\image.png "mlp_vgg/1")

VGG16_Finetuned_AllLayers\image1
![Alt text](images\images\VGG16_Finetuned_AllLayers\image1.png "1")
VGG16_Finetuned_AllLayers\image2
![Alt text](images\images\VGG16_Finetuned_AllLayers\image2.png "1")
VGG16_Finetuned_AllLayers\image3
![Alt text](images\images\VGG16_Finetuned_AllLayers\image3.png "1")
VGG16_Finetuned_AllLayers\image4
![Alt text](images\images\VGG16_Finetuned_AllLayers\image4.png "1")
VGG16_Finetuned_AllLayers\image
![Alt text](images\images\VGG16_Finetuned_AllLayers\image.png "1")