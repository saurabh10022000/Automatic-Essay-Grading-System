# Automatic-Essay-Grading-System


# Amazon Musical Instruments Reviews Multiclass Classification


In this project, I have implemented Neural Network and Random Forest classification algorithm in order to grade essay. 

## Dataset

The data set can be downloaded by following link [Data](https://www.kaggle.com/c/asap-aes/data?select=training_set_rel3.xlsx)

## Data Processing

The data is processed by converting in integer sequence using tokenizer and word_index function and then padded and truncated for eg lets say that if the review is of 10 words and another is of 12 words now to make sure that the length will remain same we have use padding and truncating and fixed the length of the training and test sequences which will be explained in notebook.

Example of a training example how it is converted in integer from text.

```
[4, 80, 7, 6, 237, 165, 2, 39, 13, 12, 140, 143, 4, 1462, 2, 1749, 1426, 389, 328, 9, 17, 655, 60, 9, 12, 722, 97, 140]
I used it to hold down the strings on my bass while I adjusted the truss rod. Worked perfectly for that purpose. Works for my four string bass
```



