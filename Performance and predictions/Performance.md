## Performance and predictions
The figures below illustrate the training progress of the U-Net model across multiple epochs. The plots capture training vs validation loss, training vs validation Jaccard coefficient, training vs validation accuracy and training vs validation Dice coefficient, providing insights into how well the U-Net model learnt over time.

<img src="sample images/unet_loss.png" alt="Unet_loss" width="400"/>

<img src="sample images/unet_dice_coef.png" alt="unet_dice" width="400"/>


Below two plots shows the training vs validation loss, training vs validation Jaccard coefficient, training vs validation accuracy and training vs validation Dice coefficient observed in the case of VGG19-UNet model training after various epochs.

<img src="sample images/vgg_unet_loss.png" alt="vgg_loss" width="400"/>

<img src="sample images/vgg_unet_dicecoef.png" alt="vgg_dice" width="400"/>


Next, the table below presents a detailed comparison of the loss and evaluation metrics for both the models on the validation and test datasets.

<img src="sample images/evaluation.png" alt="evaluation" width="400"/>


Lastly, we visualize the segmentation outputs by plotting the predictions of both models side by side along with the ground truth masks.

<img src="sample images/pred_1.png" alt="pred_1" width="400"/>

<img src="sample images/pred_2.png" alt="pred_2" width="400"/>

<img src="sample images/pred_3.png" alt="pred_3" width="400"/>

<img src="sample images/pred_4.png" alt="pred_4" width="400"/>

<img src="sample images/pred_5.png" alt="pred_5" width="400"/>
