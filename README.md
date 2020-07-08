# Domain Specific Academic Dataset - Extractive Text Summarization
This repository contains a collection of URLs that can be used to mine domain-specific academic datasets.

Data were used to train and test a supervised machine learning-based summarization approach presented in the paper: 

Cagliero L. & La Quatra M., *Extracting Highlights of Scientific Articles: a Supervised Summarization Approach*, Expert Systems with Applications, 2020, 113659, ISSN 0957-4174, https://doi.org/10.1016/j.eswa.2020.113659. 

Free full access (before August 26th, 2020): https://authors.elsevier.com/a/1bMgg3PiGTFJ76

Keywords: Keyword: Highlight extraction; Extractive summarization; Regression models; Text mining and analytics

This repository is intended for research purposes only. If you use this collection in your research work please cite:

```
@article{CAGLIERO2020113659,
title = "Extracting highlights of scientific articles: A supervised summarization approach",
journal = "Expert Systems with Applications",
volume = "160",
pages = "113659",
year = "2020",
issn = "0957-4174",
doi = "https://doi.org/10.1016/j.eswa.2020.113659",
url = "http://www.sciencedirect.com/science/article/pii/S0957417420304838",
author = "Luca Cagliero and Moreno {La Quatra}",
keywords = "Highlight extraction, Extractive summarization, Regression models, Text mining and analytics",
```

# Organization

The source files are organized as follows:

- `urls_test_ai.txt` contains a set of URLs to access the publications part of the **AIPubSumm** test set.
- `urls_train_ai.txt` contains a set of URLs to access the publications part of the **AIPubSumm** train set.
- `urls_test_bio.txt` contains a set of URLs to access the publications part of the **BioPubSumm** test set.
- `urls_train_bio.txt` contains a set of URLs to access the publications part of the **BioPubSumm** train set.

This data format relies on specific script borrowed by the [scientific-paper-summarisation repository](https://github.com/EdCo95/scientific-paper-summarisation/tree/master/DataDownloader) parts of the paper: 
Ed Collins, Isabelle Augenstein, Sebastian Riedel. [A Supervised Approach to Extractive Summarisation of Scientific Papers](https://arxiv.org/abs/1706.03946). To appear in Proceedings of CoNLL, July 2017.
