## Introduction
Mumbai and Delhi are two major cities in India. Both cities become a center of attention for residential, job employment, tourism, education, shopping and sports activity. Both cities are well known in India, and become the top choice for local and foreign communities.


Brief information about both cities:  
** Mumbai**: is the capital city of the Indian state of Maharashtra. According to United Nations, Mumbai is the second most populous city in India after Delhi and fourth most populous city in the world after Tokyo, Delhi and Shanghai with a population of 21.4 millions as of 2016.[15] As per Indian government population census of 2011, Mumbai is the most populous city in India with an estimated city proper population of 12.5 million living under Municipal Corporation of Greater Mumbai.[16] . (source: https://en.wikipedia.org/wiki/Mumbai)  

**Delhi**: officially the National Capital Territory of Delhi (NCT), is a city and a union territory of India containing New Delhi, the capital of India.[18][19] It is bordered by Haryana (Gurugram, Faridabad, Jhajjar and Sonipat) on three sides and by Uttar Pradesh (Gautam Budh Nagar, Ghaziabad and Baghpat) to the east. The NCT covers an area of 1,484 square kilometres (573 sq mi). According to the 2011 census, Delhi's city proper population was over 11 million,[7] the second-highest in India after Mumbai,[20] while the whole NCT's population was about 16.8 million. (source: https://en.wikipedia.org/wiki/Delhi)



## Objective
In this project, we will study in details the area classification using Foursquare data and machine learning segmentation and clustering.
The aim of this project is to segment areas of Mumbai and Delhi based on the most common places captured from Foursquare. 

Using segmentation and clustering, we hope we can determine:
1. the similarity or dissimilarirty of both cities
2. classification of area located inside the city whether it is residential, tourism places, or others

## Data
The data acquired from wikipedia pages and restructure to csv file for easier manipulation and reading. Both files uploaded to my github for references. Link to the files are:

- [Mumbai District Data](https://data.gov.in/node/356801/download)
- [Delhi District Data](https://data.gov.in/node/356801/download)

Another aspect to consider for this project is the Foursquare data. I believe that the data as good as provided, meaning although we are using Foursquare data for segmentation and clustering, the amount and accuracy of data captured can't 100% determine correct classification in real world.

To start, let's get and look at the data. I've already downloaded it, so let's read it (from local drive) and load it to dataframe:

