# Probing the notMNIST dataset
---
## about the data:
The data set consists of glyphs taken from publically available fonts. There are 10 classes A,B...J. Blow are a few axamples of A
![Example of A](http://yaroslavvb.com/upload/notMNIST/nmn.png)


There are two variants, notMnist Large, which is not clean and consits of about 500k glyphs of each class and notMnistsmall, which is handpicked to be more clean. Two parts have approximately 0.5% and 6.5% label error rate. [[1](#blog_dest)] 


## Abstract:
*We attempt to achieve better results than previously obtained 89% with logistic regression on top of stacked auto-encoder with fine-tuning[[1](#blog_dest)] . We intend to do this by applying various finetuned pre-trained models and by building custom models using the keras API. This is quite a challenging tas as the glyphs in the large dataset are dirty and requires a lot of cleaning. We shall attempt to over come this and use the data as is to get the best results possible.  





<b>References</b>
<a id='blog_dest'></a>
>**notMNIST dataset**
>
>Yaroslav Bulatov .[[notMNIST dataset](http://yaroslavvb.blogspot.com/2011/09/notmnist-dataset.html)]
