# Final Year Project


## Introduction

 This project deals with the analysis of characters of the book, predicting their attributes and relationships amongst them. During the adaptation of a novel/book in any form, there goes a lot of human effort, which proves to be cumbersome and unwanted. Also, the human brain tends to ignore several minor details about the happenings/characters in the book. The above forth mentioned scenario can often lead to inaccuracy in the plot of the adaptation. The project is therefore an innovation that aims at aiding an easy and accurate adaptation of a book, thus making the process a whole lot simpler and precise. The model aims at scanning the humongous amounts of texts present in the book. Post scanning, the model will show interesting insights which are derived from the given book by applying a variety of analytical techniques based on a combination of natural language processing, sentiment/emotion analysis, and social network analysis method


## Repository Layout

Regarding the layout of the repository, the project has been organized into three folders:-

1. __Human Names Generator__ - This folder consists of notebooks which are responsible for generating a master CSV file of all possible human names.
 	1. There are __three__ CSV files, _Indian-Female-Names.csv_, _Indian-Male-Names.csv_ and _Foreign-Names.csv_ which have been used.
 	2. The iPython Notebook _Names List Generator.ipynb_ is responsible for generating the list of human names which are stored into a pickle file.
 	3. The pickle file _humanNames.txt_ is the output of this particular stint and is used in the further course of the project.

2. __Any Book__ - This folder performs analysis on an English novel, named [Sense and Sensisbility](http://www.gutenberg.org/cache/epub/161/pg161.txt). 
	1. The file _textFile.txt_ is the UTF-8 encoded version of the novel.
 	2. The iPython Notebook _Word CSV Generator.ipynb_ generates a CSV file [words.csv](https://drive.google.com/file/d/17Rk996NTGCyymD7XGR2HR3hnRyXB1yxo/view?usp=sharing) which is used further in the course to perform analysis.
	3. The iPython Notebook _Character List Generator.ipynb_ generates the list of main characters in the book and saves it in _characterList.txt_
	4. The iPython Notebook _Word Cloud Generator.ipynb_ generates word cloud for any specified character The folder __Word Clouds__ consists of results of _Word Cloud Genrator.ipynb_ run on various characters.
	5. The iPython Notebook _Sentiment Analysis.ipynb_ performs sentiment analysis, using _NRC_emotion_lexicon_list.txt_ and generates visualisations to facilitate proper depiction of sentiment throughout the book.
	

3. __Mahabharata__ - This folder performs analysis on the epic [Mahabharata](https://www.sacred-texts.com/hin/maha/index.htm).
	1. The folder __data__ consists of the raw text data. It consists of all 18 books, which have been combined into _mahafull.txt_
	2. The iPython Notebook _Word CSV Generator.ipynb_ generates a CSV file [words.csv](https://drive.google.com/file/d/1hDrhOs_PnIeS9Fg04-ODqqR5iCydZYNh/view?usp=sharing) which is used further in the course to perform analysis.
	3.  The iPython Notebook _WordCloud For Any Character.ipynb_ generates word cloud for any specified character The folder __Word Clouds__ consists of results of _Word Cloud Genrator.ipynb_ run on various characters.
	4.  The iPython Notebook _Relation Generator For Any Character.ipynb_ generates the network for the specified characters, i.e. depicts the characters in the book with whom that particular character had encounters.
	5.  The iPython Notebook _Mahabharat Sentiment Analysis.ipynb_ performs sentiment analysis, using _NRC_emotion_lexicon_list.txt_ and generates visualisations to facilitate proper depiction of sentiment throughout the book, as well as [chap_with_emo_scores_normalized.csv](https://github.com/cruzer3008/Final-Year-Project/blob/master/Mahabharata/chap_with_emo_scores_normalized.csv) which shows the degree of every emotion in every book.
	6.  The iPython Notebook _LDA_Mahabharata.ipynb_ performs LDA Analysis for topic modelling on Mahabharata. And generates an [interactive output](https://htmlpreview.github.io/?https://github.com/cruzer3008/Final-Year-Project/blob/master/Mahabharata/lda.html)

## Outputs
<div align="center">

#### Sentiment Analysis For Mahabharata 

![Sentiment Analysis Mahabharata](https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/Mahabharat%20Sentiment.png?raw=True)

- - -
#### Word Cloud for Lord Krishna

<div align="center">
<img src="https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/WordCloud%20Krishna.png?raw=True" >
</div>

- - -
#### Topic Modelling Output for Mahabharata

![Sentiment Analysis Mahabharata](https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/LDATable.png?raw=True)
- - -
#### Topic Modelling Interactive Output Screenshot

![Sentiment Analysis Mahabharata](https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/LDAOutput.png?raw=True)
- - -
#### Sentiment Analysis for Sense and Sensibility

![Sentiment Analysis Mahabharata](https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/AnyBook%20Sentiment.png?raw=True)
- - -
#### Character Cloud for Fanny from Sense and Sensibility

<div align="center">
<img src="https://github.com/cruzer3008/Final-Year-Project/blob/master/Results/WordCloud%20Fanny.png?raw=True" >
</div>

</div>


## Tools

1. __Python__ - NLTK, spaCy, Seaborn, Matplotlib
2. __Algorithms__ - VADER, LDA
3. __Development Platform__ - Jupyter

## Project Report

[Report](https://docs.google.com/document/d/1vuc7b_ztkjfG_3SR5wm116iDKeY01AhrtWPvK-5CkRY/edit)


