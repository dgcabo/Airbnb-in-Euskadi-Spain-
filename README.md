# Airbnb business analysis in Euskadi (Spain)
Here you will find all the relevant information regarding our Airbnb study.
We recommend starting with the section "Project Motivation".

### Index
- [Installations](#Installations)
- [Project motivation](#Project-motivation)
- [File descriptions](#File-desciption)
- [Interacting with the data](#Interacting-with-the-data)
- [Others](#Others)
- Conclusions
  
### Installations
It is crucial to have the following tools and libraries installed:
- The latest version of Python
- Jupyter Notebook
- Libraries such as numpy, pandas, matplotlib.pyplot, seaborn, and ast — although these will be automatically imported when running the Jupyter Notebook file.

### Project motivation
This project has aimed to analyze the current situation of Airbnb's business in this region of Spain, with the main objective of identifying the area or town with the highest profitability. This is intended to serve as a guiding model for future real estate investments in the area.
For this purpose, the following question will be answered:
1. Which are the areas in Euskadi have the highest occupancy rates throughout the year?
2. Which areas in Euskadi show the highest demand relative to the number of available accommodations, indicating that demand significantly exceeds supply?
3. What review-related factors are most influential in driving Airbnb property demand, and how should an Airbnb property be designed to maximize its potential demand?

The file related to this study belong to airbnb, and have been donwloaded from the official website.

### File descriptions
There are two different files in this repository:

File 1: A CSV file containing input data from Airbnb, including comprehensive information related to the Airbnb business in Euskadi (Spain).
File 2: A Jupyter Notebook where the study will be carried out.

### Interacting with the data
Feel free to open each of these files for better understanding of the whole process.
The Jupyter Notebook will guide you through the different sections and comments of this study, allowing you to clearly understand the processes that have been carried out and how the conclusions were reached.
More Information regarding the process aswell as the answers and results can be found in the following [Blog post](https://medium.com/@dgcabo1/text-cf63bcf4246f)

### Others
This study is the final project of my data science course from Udacity.

### Conclusions
**Question 1:** here are 35 locations with an estimated occupation of 255 day per year in Euskadi:
Aramaio, Areatza, Barakaldo, Beasain, Berastegi, Bermeo, Berreaga-Mendi, Bilbao, Donostia / San Sebastián, Elgoibar, Gasteiz, Getxo, Guernica, Irun, Oiartzun, Orio, Pasaia, Sestao, Sopelana, Urnieta, Usurbil, Vitoria-Gasteiz, Zizurkil, Zumaia.  
**Question 2:** The answer to this question is Donostia (Sans Sebastian), Spain.  
**Question 3:**  
- Apart from other top features (sh. Jupyter), we can observe that guests pay special attention to: Reviews related to cleanliness, Check-in options, Communication with the host.
- Based on the analysis of how individual values of bathrooms, beds, accommodates, and the types of property and room influence the estimated occupancy, we conclude that the optimal combination of features to achieve the highest estimated occupancy includes:
**Entire rental unit for 2 people, with 2 beds and 1 bathroom.**

