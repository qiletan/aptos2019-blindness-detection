# aptos2019-blindness-detection
My personal solution for the aptos2019-blindness-detection Kaggle competition where I achieved Rank 72th (top 2.4%)

I posted writeup on https://www.kaggle.com/c/aptos2019-blindness-detection/discussion/107975#latest-621103 where I hightlighted my approach and some key findings. 

## How to use my notebooks:
I had to break the whole appaorch into two parts: model training and inference, due to the fact that this is a synchronous Kernels-only competition and I wanted to utilise my local machine to train the models.

So to get similar results as mine, run the 01_model_training.ipynb and save the model weights. Then run the 02_inference.ipynb to score the test images on Kaggle's Kernel

Total run time should be less than 5 hours on a GTX 1080 for training and 2.5 hours for inference on Kaggle site.

