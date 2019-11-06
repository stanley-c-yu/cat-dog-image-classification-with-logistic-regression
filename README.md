# cat-dog-image-classification-with-logistic-regression
Image classification of the cat-dog dataset from Kaggle using logistic regression.

The dataset used to train and test the model consists of 25,000 labeled images from the training zip folder provided via Kaggle's repository for the "Dogs vs. Cats" dataset.  Kaggle's repository also includes a test zip folder that contains unlabeled images that can be used to test the final model for robustness.  

This project was mostly a proof-of-concept job, as well as an opportunity to gain some valuable experience in image preprocessing that could be used in other image classification projects, so certain preprocessing measures that might have improved model accuracy were not taken.  Because of this, the model's accuracy currently stands at about 55.8%.  

If I have time, I believe performance could be improved by enabling "stratify" in the "train_test_split" method to ensure even distribution of classes, as well as by standardizing the data before model fitting and testing.  

Special thanks to Harrison "sentdex" Kinsley and Michael Galarnyk for their amazing tutorials regarding image classification and preprocessing.  My work here was heavily influenced by their work.  
