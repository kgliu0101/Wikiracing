# Wikiracing
Wikiracing is a game played on wikipedia. Given a starting article and an ending article,
the objective of a wikirace is to get from the starting article to the ending article by only clicking
on links occurring in the main bodies of wikipedia articles.

A python script in this repo has been developed to build a path for wikiracer automatically. It takes 
urls of "start" and "end" articles from a JSON file and record a group of urls between. By clicking them
in proper order, you will be linked to the "end" page from the "start" page.

Example:
  - Start - [https://en.wikipedia.org/wiki/Plasmodium_falciparum](https://en.wikipedia.org/wiki/Plasmodium_falciparum)
  - End - [https://en.wikipedia.org/wiki/Algorithm](https://en.wikipedia.org/wiki/Algorithm)

# How to execute
Python 3

# Files

# Algorithm
Bi-directional BFS
