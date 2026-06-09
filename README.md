# Graph Embeddings for Yucatec Maya

## Research Context
This repository contains the dataset and resources associated with the study: **“What do Mayan Embeddings Capture? Overcoming the Long-Tail through Graph Topologies and Native Expert Validation”**.

## Abstract
This work addresses a central challenge in Natural Language Processing for low-resource and morphologically rich languages: the development and evaluation of semantic representations under conditions of limited data availability. Focusing on Yucatec Maya, we present the first systematic evaluation of word embeddings for this language and introduce a graph-based methodology designed to mitigate the long-tail distribution of rare inflected forms.

The study makes several contributions:
1. **Corpus Construction:** We processed a multi-source corpus of 717,471 tokens for Yucatec Maya.
2. **Methodological Innovation:** We developed and evaluated semantic representations using graph topologies, comparing them against widely used distributional approaches.
3. **Gold Standard:** We created the first expert-validated gold standard for semantic similarity in Yucatec Maya.
4. **Open Science:** We release the resulting embeddings and evaluation resources to facilitate future research on Mayan and other low-resource languages.

## Repository Contents
The repository includes the following:
* `/embeddings/`: Compressed (.zip) files containing the word embeddings in various dimensions (e.g., 50d, 100d, 200d, 250d, 300d).
* `/evaluation/`: Contains the expert-validated Gold Standard used for semantic evaluation, including the 90 word pairs and their corresponding human similarity scores.
* **Corpus:** The source corpus used in this study is not distributed here due to copyright considerations. 

> **Note:** Large files are managed using **Git LFS**. To download the embeddings, please ensure you have [Git LFS](https://git-lfs.github.com/) installed and run `git lfs pull` after cloning.

## Validation and Acknowledgments
The data were validated by expert linguists under a blind evaluation protocol. The authors wish to express their deep gratitude to **Lorena Pool Balam**, MA in Mayan Psycholinguistics, for her leadership as principal evaluator and expert curator of the Gold Standard. 

We also sincerely thank our fellow professors, linguists, and native Mayan speakers: **Jesus Edilberto Sunza Pech**, **Rosa Couoh Pool**, **Didier Chan Quijano**, and **Irma Pomol Cahum**. Their linguistic expertise and profound cultural knowledge were fundamental in ensuring the quality and integrity of this study.

## Citation
This work is currently under review. Please check back later for the official citation, or contact the authors if you wish to reference these resources in your ongoing research.

