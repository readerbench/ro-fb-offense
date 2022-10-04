# RO-FB-Offense
FB-RO-Offense corpus, an offensive speech dataset containing 4,455 user-generated comments from Facebook live broadcasts,  annotated not only for coarse-
grained binary detection tasks but also fine-grained, based on the degree of the offense.

By scraping the comments on certain political themed live broadcasts on Facebook, we gathered
more than 30 thousand comments from over 20 different broadcasts.

In the annotation process we kept only messages with a minimum length of 15 characters and a maximum length
of 187 whereas comments containing URLs or phone numbers were also removed. 
This left 8017 entries for the final annotation process.

# Corpus Statistics

The comment length distribution over the corpus:

![image](https://user-images.githubusercontent.com/863810/193778008-f7f8f0be-2d12-42fd-91f8-5635ae527567.png)


The Label distribution on the full 8000 comments:

![image](https://user-images.githubusercontent.com/863810/193778342-ff380a03-9e93-49c4-8723-89a02a289a3e.png)

In this repository we provide a reduced, more balanced dataset with this distribution 

| Assigned label | # Comments | % of Total | 
|----------------|------------|--------|
|OTHER | 2,673 | 60.00%|
|INSULT | 769 | 17.26%|
|ABUSE | 834 | 18.72%|
|PROFANITY | 179 | 4.01|
| | | |
|Total|4,455|100.00%|








# Paper citation
```
@inproceedings{busuioc2022fb-ro-offens,
  title={FB-RO-Offense – A Romanian Dataset and Baseline Models for detecting Offensive Language in Facebook Comments},
  author={ Busuioc, Gabriel-Razvan and Paraschiv, Andrei and Dascalu, Mihai},
  booktitle={International Symposium on Symbolic and Numeric Algorithms for Scientific Computing (SYNASC) 2022},
  year={2022}
}
```
