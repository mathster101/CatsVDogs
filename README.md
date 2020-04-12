# CatsVDogs
Pytorch based CNN to identify cats and dogs


Find the dataset here -> https://drive.google.com/open?id=181j8UCrxIuW50YKpVuDo4EosYuiQn5zN

The dataset essentially contains ~24000 images of cats and dogs together. 
The images have been converted to monochrome 50x50 matrices and stored. The way its currently stored enables it to be compatible with pytorch's dataloader utility.

On a isolated validation batch of size 400, the following results were obtained.

![error and accuracy per epoch](images/analytics.png)
Note: Max accuracy here was 87.75%.
