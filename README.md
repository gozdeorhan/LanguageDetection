# Language Detection

This project is done in order to propose a machine learning system to classify words into their languages, namely Turkish or English.

The project is executed for a case study where 2 csv files were given: Dictionary_Turkish (2235 words) and Dictionary_English (21666 words). Unfortunately the files are not permitted to be shared publicly. Both csv files consist of 4 to 6 characters long well-written, genuine words in Turkish and English.

The proposed system is an *SVM classifier* preeceded by a simple if-else statement. 

- First, if the string contains one of the following: q, w, x, the word is classified as English. 
- If not, then, the word is fed into to the classifier to be labelled. 

# Future Work

The proposed ML system is significantly successful identifying English words, which may be an indicator that if a larger Turkish corpus can be utilized, classifier would be enable to succesfully detect language. In addition, word-length constraint in vectorization is challenging since it limits the algorithm's ability to detect the language of longer words.

# Dataset

Datasets were provided by a private company which is why publicly sharing them is not allowed. However, a new dictionary files will be created by myself and the repo will be updated accordingly. Until then, you can try the code yourself if you have your own datasets! Please enjoy :)
