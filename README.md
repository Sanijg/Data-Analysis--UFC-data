# Data-Analysis--UFC-data
Here, whole process of data mining (Data Understanding, Data Preparation, Modeling, and Evaluation) is done. Scraped raw data is cleaned and some statistical analysis is done. **'What is the best fighting style?'** is answered based on the data.

**Two different data sets were merged for effectiveness**

# Fighters dataset: 
This contains the general information on the fighters oneself. A snippet of this data set is as follows:
![fighters_snippet](fighters_snippet.PNG)


# Fights dataset:
This contains the collection of all the fights a particular fighters has under the promotion of Ultimate Fighting Championship(UFC).
A snippet of this data set is as follows:
![fights_snippet](fights_snippet.PNG)

Real data is never clean. We need to make sure we clean the data by converting or getting rid of null or missing values. Then extracting the essential attributes from each dataset and merging together to form a single dataset with fighters and their personal attributes along with the collection of their fights with its own attributes. Something like:
![merged](merged.PNG)
