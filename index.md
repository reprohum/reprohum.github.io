---
layout: splash
permalink: /
excerpt: "ReproHum "
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/bc.png
---

# The ReproHum Project
The ReproHum projects aims to define, measure, and improve reproducibility in the field of Natural Language Processing.  The project is funded under [EPSRC grant EP/V05645X/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/V05645X/1).  Reproducibility is one of the cornerstones of scientific research yet experimentla results for NLP systems are seldom reproduced.  Even when they are, results tend to be worse than in the original publication.

The ReproHum project aims improve the current reproducibility situation in NLP.  The main goals are:
* Diagnose the extent of the reproducibility problem in NLP and identify barriers to carrying out replication work.
* Develop a methodological framework for testing the reproducibility of human evaluations in NLP.
* Design then perform the ReproHum multi-lab study where partner labs reproduce human evaluation results from the last 10 years, covering a variety of areas within NLP.  In addition, continue the ReproGen shared task.
* Provide guidance on reproducibility to the NLP community and build a concensus within the community on how NLP as a field can continue to improve in this regard.


## Project overview
The project will take place over the 18 months from April 2022.  There are six work packages.


### Survey of NLP researchers
We will shortly be conducting a surveys on the attitudes towards reproducibility in NLP, as well as the barriers that are faced by researchers.


### ReproGen
The ReproGen shared task was first run as [ReproGen 2021](https://reprogen.github.io/2021) and is being run again as [ReproGen 2022](https://reprogen.github.io).  There are two tracks, one where participants can attempt reproduction of human or automated evaluations from a common list of published papers, and a second where participants can reproduct their own prior work.


### Multi-lab reproducibility study
A major part of the ReproHum project is a large multi-lab study where partner labs from across the world will reproduce results from a variety of papers from the last 10 years.  We are still open to new partner labs joining, please contact the organisers (links above).

Partner labs will run reproductions of prior results from a selection of papers.  For each paper, reproduction will by attempted by two labs in the first [degree of reproducibility](https://aclanthology.org/2020.inlg-1.24), with evaluation in increasing degree applied to any papers that are reproducable in a lower degree.


### Quantified Reproducibility Assessment
To obtain a single score estimating the degree of reproducibility of a given system and evaluation measure we will carry out a quantified reproducibility assessment (Belz, 2021).  We will calculate the coefficient of variation with adjustment for small sample size.  Code implementation can be found [here](https://github.com/asbelz/coeff-var)


## ReproHum project & pre-project
* Anya Belz. 2021. [Quantifying reproducibility in NLP and ML](https://dblp.uni-trier.de/rec/journals/corr/abs-2109-01211.html?view=bibtex). CoRR, abs/2109.01211.
* Anya Belz, Shubham Agarwal, Anastasia Shimorina, and Ehud Reiter. 2021a. [A systematic review of re-producibility research in natural language processing](https://aclanthology.org/2021.eacl-main.29).  In Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics: Main Volume, pages 381–393, Online.  Association for Computational Linguistics.


## Other interesting papers on reproduction

* Anya Belz, Anastasia Shimorina, Shubham Agarwal, and Ehud Reiter. 2021b.  [The ReproGen shared task on reproducibility of human evaluations in NLG: Overview and results](https://aclanthology.org/2021.inlg-1.24). In Proceedings of the 14th International Conference on Natural Language Generation, pages 249–258, Aberdeen, Scotland, UK.  Association for Computational Linguistics.

* Margot Mieskes, Karën Fort, Aurélie Névéol, Cyril Grouin, and Kevin Cohen. 2019. [Community perspective on replicability in natural language processing](https://aclanthology.org/R19-1089). In Proceedings of the International Conference on Recent Advances in Natural Language Processing (RANLP 2019), pages 768–775, Varna, Bulgaria.  INCOMA Ltd.

* Monya Baker. 2016. [Is there a reproducibility crisis?](https://www.nature.com/articles/533452a)  Nature, 533:452–454

* Open Science Collaboration. 2015.  [Estimating the reproducibility of psychological science](https://www.science.org/doi/10.1126/science.aac4716), 349(6251).
