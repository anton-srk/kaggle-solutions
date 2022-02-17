# Kaggle solutions

## [Sartorius cell segmentation](https://www.kaggle.com/c/sartorius-cell-instance-segmentation)  
(top 7%) Custom UNet implementation based on the [Cellpose model](http://www.cellpose.org/)  

## [Jigsaw Rate Severity of Toxic Comments](https://www.kaggle.com/c/jigsaw-toxic-severity-rating)  
(top 5%) Two steps process:
* Pretrain roberta on the [Jigsaw Unintended Bias in Toxicity Classification](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data)
data for multilabel classification
* Train the model from the previous step on [ruddit comment pairs dataset](https://www.kaggle.com/konradb/ruddit-pairs-dataset)
with margin ranking loss