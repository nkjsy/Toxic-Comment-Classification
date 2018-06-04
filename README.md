# Toxic-Comment-Classification
kaggle challenge to identify and classify toxic online comments

This is the kaggle challenge. Download data here:
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

Different models built including tf-idf, CNN and RNN. All in the 11 jupyter notebooks. 
Model details see the word. M11 is the best single model. Data visualization also in M11.
A final merger was applied. The best score is 0.9832 achieved by merging of 2,8,9,10,11.

Model file and submission file:
https://pan.baidu.com/s/1WBtGu_t5pdvA0OqmowjORA

The result is not quite good. Some points to improve:
1: Build a larger vocabulary by increasing max_feature
2: Include longer sentences by increasing max_len
3: Use more and larger pretrained word vectors.
4: Spell correction either by TextBlob or function by myself. This will take very long time, about one day running on CPU.
5: Data augmentation by translation to another language and back to English. Connection failure due to google blockage. 
The 4 and 5 are already implemented in Deprecated clean text.ipynb
