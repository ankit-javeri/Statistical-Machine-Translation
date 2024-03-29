# Statistical-Machine-Translation

Final semester project - **Translation of text from French to English**

# Description

- **Objective:** Language translation from French to English which would ease in sharing of knowledge from diverse subjects.
- **Methodology:** Understanding of lexical machine translation models such as word based translation (IBM Models for word alignments), phrase based translation (phrase extraction for phrase alignments).
- **Implementation:** Data preprocessing, handling partially missing data, implementation of IBM Model1 to learn word alignments from parallel corpus for word based machine translation.
- **Results:** Trained IBM Model1 was hardly able to learn word alignments as it was trained on only 1000 sentences (0.0526% data).
- **Improvements:** Train IBM Model1 on entire data with higher computational power & implementation of phrase based models and tree based models.

# Data Source 
The data for this project is taken from **[European Parliament Proceedings Parallel Corpus 1996-2011](https://www.statmt.org/europarl/)** 

Direct link to dataset [download](https://www.statmt.org/europarl/v7/fr-en.tgz) (size 194MB)


# SMT IBM Model1 - Learning Alignments (Improved on earlier Shortcomings)

Improvised codes to learn the alignments better than earlier.


