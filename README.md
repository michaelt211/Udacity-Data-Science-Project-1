# Udacity-Data-Science-Project-1



The data used is from the 2020 stack overflow developer survey where almost 65,000 developers answered a series of question related their demographics the tools they use, and what they value and how they study. 

This project looks at 3 mean questions: 

1. Are they developers in United States paid more or less the same than rest of world
2. Are the developers in the United States happy when compared to the rest of the world
3. What drives developers in the United States to look for a new job vs. The Rest of the World (i.e., what's most important to American job seekers)


The project pulls all the survey data from Google Drive using the library Googledrivedownloader.  It also explores various aspects of the data and cleans the data by handling missing values. It then shapes the data then project then plots the results. The data preparation, modeling, and evaluation process is done for each of the 3 questions. 

Summary of Analysis 

Through the anlysis we discovered these core insights: 
1 - Developers in the U.S. are more highly compensated than developers not in the U.S.
2 - Developers in the U.S. are more satisfied than developers not in the U.S.
3 - Developers in the U.S. are more likely to search for a new job as the results of trouble with leadership than developers not in the U.S. 

We developed a blog post examining these questions in detail this is the link to the post: 
https://medium.com/@michael.preston/how-to-use-stackoverflow-data-to-compare-software-developer-compensation-satisfaction-and-3ca9ae5b4456



From the plots the answers to the business questions we posed is clear so no further analysis was needed. 


The project pulls all the survey data from Google Drive using the library Googledrivedownloader.  It also explores various aspects of the data and cleans the data by handling missing values. It then shapes the data then project then plots the results. The data preparation, modeling, and evaluation process is done for each of the 3 questions. From the plots the answers to the business questions we posed is clear so no further analysis was needed. 


The all files used for the analysis are included in the respository and they are the following: 

so_survey_2020.pdf
survey_results_public.csv
survey_results_schema.csv 

The Anaconda distribution and Jupyter notebook was used to do the analysis. 

Acknoledgements 


https://stackoverflow.com/
https://docs.python.org/3/

The developers of  the following packages used to create the project and their respective documentation: 

Utility 
warnings
Requests
StringIO

Data Wrangling 
Googledrivedownloader

Data Manipulation 

Pandas
Numpy 

Plotting 
Matplotlib
Seaborn 

