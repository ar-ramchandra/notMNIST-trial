# Probing the notMNIST dataset
---
## about the data:
The data set consists of glyphs taken from publically available fonts. There are 10 classes A,B...J. Blow are a few axamples of A
![Example of A](http://yaroslavvb.com/upload/notMNIST/nmn.png)



There are two variants, notMnist Large, which is not clean and consits of about 500k glyphs of each class and notMnistsmall, which is handpicked to be more clean, have about 1,800 glyphs per class. both parts have approximately 0.5% and 6.5% label error rate. [[1](#blog_dest)] 


## Abstract:
*We attempt to achieve better results than previously obtained 89% with logistic regression on top of stacked auto-encoder with fine-tuning[[1](#blog_dest)] . We intend to do this by applying various finetuned pre-trained models and by building custom models using the keras API, and the openCV module to make live predictions on actual hand-written alphabets.* 


With a trial and error uproach in mind, the following attempts were made to build a neural network from scratch to predict the alphabets;


## Custom Convolutional Neural networks:

### Initial model:


![attempt 1](C:\Users\offic\Desktop\attempt1.jpg)




<b>References</b>
<a id='blog_dest'></a>
>**notMNIST dataset**
>
>Yaroslav Bulatov.[[notMNIST dataset](http://yaroslavvb.blogspot.com/2011/09/notmnist-dataset.html)]
