# Final Year Project

----

##Introduction

 This project deals with the analysis of characters of the book, predicting their attributes and relationships amongst them. During the adaptation of a novel/book in any form, there goes a lot of human effort, which proves to be cumbersome and unwanted. Also, the human brain tends to ignore several minor details about the happenings/characters in the book. The above forth mentioned scenario can often lead to inaccuracy in the plot of the adaptation. The project is therefore an innovation that aims at aiding an easy and accurate adaptation of a book, thus making the process a whole lot simpler and precise. The model aims at scanning the humongous amounts of texts present in the book. Post scanning, the model will show interesting insights which are derived from the given book by applying a variety of analytical techniques based on a combination of natural language processing, sentiment/emotion analysis, and social network analysis method

---- 

##Repository Layout

Regarding the layout of the repository, the project has been organized into three folders:-

1. __Human Names Generator__ - This folder consists of notebooks which are responsible for generating a master CSV file of all possible human names.
 1. There are __three__ CSV files, [Indian-Female-Names.csv](Human Names Generator/Indian-Female-Names.csv/), _Indian-Male-Names.csv_ and _Foreign-Names.csv_ which have been used.
 2. The iPython Notebook _Names List Generator.ipynb_ is responsible for generating the list of human names which are stored into a pickle file.
 3. The pickle file _humanNames.txt_ is the output of this particular stint and is used in the further course of the project.

2. __Any Book__ - This folder performs analysis on an English novel, named [Sense and Sensisbility](http://www.gutenberg.org/cache/epub/161/pg161.txt)
