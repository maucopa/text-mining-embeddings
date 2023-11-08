# Identification of professions &amp; occupations in Health-related Social Media
In this project, we will work with a set of real data published for the shared-task [ProfNER](https://temu.bsc.es/smm4h-spanish/), held in 2021. Specifically, we will use the textual data from subtask 1, which focuses on text classification. This dataset consists of Spanish tweets with a numerical label assigned, representing the presence (value 1) or absence (value 0) of mentions of professions in the tweet. If you are interested, the process of obtaining, selecting, and annotating the data is described [in this link.](https://temu.bsc.es/smm4h-spanish/?p=4003).

For the project, we will train different classification models to correctly classify the tweets. To do this, it will be necessary to create and use data preprocessing functions, apply text embedding vectorization strategies, and train/evaluate classification models.

-	**Exploratory Analysis, Data Preprocessing, and Normalization:**:
        -	The project includes an exploratory analysis of the data, such as the number of documents, distribution graphs of lengths, and word clouds.

    -	It also includes functions for text normalization that allow removing stop words, punctuation symbols, and lemmatization.

-	**Text Vectorization:**

    - As a text vectorization strategy, we use embeddings, taking into account that the embedding should be in Spanish.

-	**Training and Validation of the System**
  -	In the model training process, we test two classification models. First, we estimate the performance of the algorithms in a general way and then select the best one to fine-tune the hyperparameters.
