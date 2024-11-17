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