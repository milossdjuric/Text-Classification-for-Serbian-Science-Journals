# Text-Classification-for-Serbian-Science-Journals

**Project problem**
- The goal of this project is to use different text classification algorithms to classify text paragraphs from Serbian scientific journals into different categories.
- The categories can be as follows:
  - Architecture and Civil Engineering
  - Biology
  - Economy
  - Geoscience
  - Chemistry
  - Informatics and Electrical Engineering
  - Mathematics
  - Medicine
  - Agriculture

**Algorithms** 
- Multinomial Naive Bayes, SVM, KNN

**Data**
- Dataset was self-made using materals from an online archive Srpski Citatni Indeks, which contains numerous published Serbian scientific journals.
- Link of their website: https://scindeks.ceon.rs/
- Dataset CSV file: [serbian_science_journals_dataset.csv](https://github.com/milossdjuric/Text-Classification-for-Serbian-Science-Journals/files/12064208/serbian_science_journals_dataset.csv)
 

**Performance measurement metric**
- Performance is measured using accuracy and macro average metrics.

**Solution validation**
- The dataset is divided into 70% for the training set, 15% for the validation set, and 15% for the test set.

**Dependencies**
-   MatplotLib
-   NLTK
-   Numpy
-   Pandas
-   Skicit-Learn
-   SrbAi
-   Gensim
    
**Additional Dependency Installation**
- Additional python library called SrbAi is necessary to run the code. It can be downloaded from their GitHub repository: https://github.com/Serbian-AI-Society/SrbAI, and installed following instructions from their repository.

**Poster**
-
![ORI_poster](https://github.com/milossdjuric/Text-Classification-for-Serbian-Science-Journals/assets/116558460/052422e1-fdd1-4297-b1a8-40a02af44087)



**Addition to the Original Project**
-
- Addition to the original project is added by implementing Multilayer Perceptron (MLP) Classifier to the project. In the original project I intended to implement Word2Vec vectorization as well. However the performances of original algorithms were too low to be observed seriously. Because of that I added MLP to test the Word2Vec vectorization. Besides Word2Vec, MLP is also tested with the two original vectorizations: Count and TF-IDF.