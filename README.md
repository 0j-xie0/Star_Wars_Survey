# Star Wars Survey
### •To explore survey data collected from fans regarding the various Star Wars movies.

# Installation
•Clone this repo to your computer.  
•Install the requirements using pip install -r requirements.txt.  
•Make sure you use Python 3.  
•You may want to install [Jupyter](http://jupyter.org/install) to run the ipynb.

# Usage
•Run the Jupyter Notebook "Star.Wars.ipynb" either in Jupyter or the IDE of your choice.

# Tasks Performed
### •Cleaned Dataset
••Removed rows with null values from 'RespondentID' column.  
••Mapping 'Yes/No' columns to Boolean.  
••Mapping checkbox columns to Boolean using dictionary method.  
••Renamed columns to be more descriptive.  
••Converted ranking columns to float.
### Retrieved Highest Ranking Movie
••Used pandas.Dataframe.mean() method to compute ranking.  
••Made bar chart of each ranking.
### Retrieved Most-Viewed Movie
••Used df.sum() method to compute the sum of each of the columns of movies seen.  
••Made bar chart of each ranking.
### Explored Data by Binary Segments
••Split data into two groups based on whether respondent is a Star Wars or Star Trek fan.  
••Analyzed and compared most-viewed movies with highest-ranked movies.
# Next Steps
•Segment data based on columns such as 'Education' and 'Location(Census Region)'.  
•Clean and explore columns which contain data on favorable and unfavorable characters of the movies.

