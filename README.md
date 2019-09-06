# Examining Gender Bias in Languages with Grammatical Gender
This repo contains the code and data used for our EMNLP-IJCNLP 2019 Paper: [Examining Gender Bias in Languages with Grammatical Gender](https://arxiv.org/abs/1909.02224). We will make some updates in the near future. If you have any questions, please don't hesitate to email us!

All the code used in this paper is contained in the jupyter notebook, and the seed words used are contained in the other text files. 
Note that we do not put embeddings used here: for original embeddings, please check [MUSE](https://github.com/facebookresearch/MUSE); for our mitigated embeddings, they can be produced following the sections in our notebook.

`xx_definitional_pairs.json` files contain the gender definitional pairs (female, male) in each language (EN=English, ES=Spanish, FR=French).

`xx_occupation_words_with_EN_translations` files contain the occupation triplets used for our experiments in the form of (feminine version, masculine version, English translations) for Spanish and French.

`WordPair_adj_EN_ES_FR` file contains the adjective triplets (EN, ES, FR) used for our word pair translation experiments.
`bias_emnlp19.ipynb` is the jupyter notebook file in Python 3.

`feminine/masculine_nouns_xx` files contain the 5000 collected grammatically feminine/masculine nouns in Spanish and French (some of them are repetitive and we remove them in our code).
