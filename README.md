# Sentiment Scraper

This script scrapes google news articles based on a keyword and gives them a sentiment score. 

Using Gnews, the main parameters to be chosen are the main keyword, search period, and searched pages. Popular buisness websites regarding finance and stocks were excluded. 

The current version of sentiment analysis works using Vader for mainly due to speed restrictions. The current output "news.csv" m,ainly made use of neural network, and use of a custom chat gpt API was tested to finally give a sentiment analysis between 0 and 4 in .4 increments, and was later expanded as a percentage. All 83 articles that were scraped (after data cleaning) were then manually reviewed to give a more accurate score, as 83 articles was not enough to properly train a neural network, regardless of the amount of nodes/layers & split between the testing and training data. 

Custom visuals and graphs were made for this project but are no longer avaiallbe as they are now the propery of Matrox.

Sentiment analysis of Matrox's digital footprint showed a average sentiment of 88 (standard deviation of 23) in the past 5 years, and a weighted average (based on relevancy by date) of 77 (standard dev of 23). 
