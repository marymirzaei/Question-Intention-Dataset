# What is the Real Intention behind this Question? Dataset Collection and Intention Classification

## Abstract:
Asking and answering questions are inseparable parts of human social life. The primary purposes of asking questions are to gain knowledge or request help which has been the subject of question-answering studies. However, questions can also reflect negative intentions and include implicit offenses, such as highlighting one's lack of knowledge or bolstering an alleged superior knowledge, which can lead to conflict in conversations; yet has been scarcely researched. This paper is the first study to introduce a dataset (Question Intention Dataset) that includes questions with positive/neutral and negative intentions and the underlying intention categories within each group. We further conduct a meta-analysis to highlight tacit and apparent intents. We also propose a classification method using Transformers augmented by TF-IDF-based features and report the results of several models for classifying the main intention categories. We aim to highlight the importance of taking intentions into account, especially implicit and negative ones, to gain insight into conflict-evoking questions and better understand human-human communication on the web for NLP applications.

## Question Intention Dataset
This repository contains the Question Intention Dataset published in ACL 2023 (_to be released by the end of July 2023_).
The dataset aims to analyze the perceived intentions behind questions, both positive and negative ones, from the reader's perspective. To investigate the underlying intention categories, we have collected a diverse set of questions from Wikipedia discussion pages. These pages provide a valuable source of real-world interaction, where questions are asked with the general goal of improving Wiki pages. However, this goal may, at times, be influenced by a personal agenda, such as showing off knowledge or disqualifying someone's work by asking questions. Therefore, studying Wikipedia discussions can serve as a plausible resource for our research.

Our dataset is built on the [Conversation Gone Awry dataset](https://convokit.cornell.edu/documentation/awry.html), encompassing the conversations on Wikipedia Talk Pages. From this dataset,
we extracted 2k questions and annotated their underlying intentions. We depicted some of our positive/neutral intention categories based on studies of questions. We went through the process of selecting and refining negative intention categories by analyzing data, defining categories based on the discovered patterns, followed by annotating questions (by two researchers independently), discussions, revising categories and guidelines, then pilot testing with workers, updating and re-annotating. We did this iterative cycle several times to select the final categories depicted in the following table and used it as a guideline for annotation.

<p align="center">
    <picture>
      <img alt="Question Intention Dataset" src="./assets/defined categories.png" width="95%">
    </picture>
</p>

## Citation

If you find this project useful in your research or work, please consider citing it:

```
@inproceedings{mirzaei2023intention,
      title={What is the Real Intention behind this Question? Dataset Collection and Intention Classification}, 
      author={Mirzaei, Maryam Sadat and Meshgi, Kourosh and Sekine, Satoshi},
      booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics",
      year={2023}
}
```

## Contact Us
For further inquiries reach us at [maryam.mirzaei@riken.jp](mailto:maryam.mirzaei@riken.jp).
