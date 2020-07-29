# NLP_Tunisian-Dialect
Tunisian dialect is significantly different from the Arabic language taught in schools and used in formal writings. However, despite its complicated written forms, it is the language used in the everyday communications and in most social Tunisian media. From here came the challenge of creating a model that can understand this dialect bytesting it on a specific Natural Language Processing (NLP) task.



0. Corpus: we collected a corpus of the Tunisian Arabic data from different different sources.

1. Tunisian word embeddings: Pre-trained word embeddings with GloVe and Skip-Gram models on Tunisian corpus.

2. Pre-trained ELMo: Pre-train the ELMo model with Tunisian Dialect data on the language model task. Once the model is trained, it can be saved and transferred to downstream task to provide deep contextual embeddings.

3. Tunisian sentiment analysis: An Elmo-based model to classify whether a tunisian sentiment is negative or positive (binary task).

4. Tunisian dialect identification: Fine-tune BERT transformer and the pre-trained Tunisian ELMo to identify the Tunisian dialect within a mixture of nearby Arabic dialects (Morroco, MSA, ...).




For further improvements, we need to collect more of data first of all and try more NLP tasks with the TD.
For more details, ideas, thoughts.. please contact me: mahmoudjarraya@gmail.com
