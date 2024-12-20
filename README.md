# Welcome to WarblerNet!

A project for classifying a subset of American Warblers based on their songs.

Created by Beck, Carly, River, & Solomon

---

## BLOG FIGURES

### Class Distribution in Training and Validation Sets  
[ClassDistributionInTrainingAndValidationSets.png](/blog_figures/ClassDistributionInTrainingAndValidationSets.png) 

Using our set of warbler species, `class_names`, and counts of each class' occurrences in our spectrograms, we made a two-group bar chart.  
**(X: warbler species, Y: species instances per set)**

---

### Training and Validation Accuracy  
[TrainingAndValidationAccuracy.png](/blog_figures/TrainingAndValidationAccuracy.png)

Using the history of our model's training process (training accuracy and validation accuracy), we made a two-group line chart.  
**(X: epochs, Y: accuracy metric)**

---

### Training and Validation Loss  
[TrainingAndValidationLoss.png](/blog_figures/TrainingAndValidationLoss.png)

Using the history of our model's training process (training loss and validation loss), we made a two-group line chart.  
**(X: epochs, Y: loss metric)**

---

### Confusion Matrix  
[ConfusionMatrix.png](/blog_figures/ConfusionMatrix.png)

Using the class names of `y_true` and `y_pred`, we made a typical confusion matrix. To plot it properly, we added a colormap, colorbar, axis ticks, colormap-dependent text, and normalized decimal values.

---

## GITHUB RUBRIC

- All necessary code is compiled on `main`
- All figures are in `blog_figures`
- All figures are explained above

---

## BLOG POST

[Read the full blog post here!](https://medium.com/@sluke9952/bird-gang-7fb9c463d97a)