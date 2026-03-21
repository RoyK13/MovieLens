# MovieLens

A genre based movie recommender system.

The system uses the MovieLens dataset from kaggle and applies a content-based filtering approach. By representing genres as feature vectors and calculating cosine similarity, it recommends movies most similar to the user's chosen genres.

# How To Run:

1. Install Required Libraries

   Open terminal and run:

   pip install pandas matplotlib seaborn statsmodels

2. Prepare Dataset

   Ensure the following files are present inside the Datasets folder:
   Datasets/
   
    ├── rating.csv
  
    ├── movie.csv
  
    ├── Movie Ratings.csv
  
    rating.csv and movie.csv are input datasets
    
    Movie Ratings.csv is generated after merging
   
3. Run Data Preprocessing Script

    Execute the following command:
    
    python Merge_Datasets.py
    
    This will:
    
    Merge datasets
    
    Generate Movie Ratings.csv

4. Run Visualization Script

    Execute:
    
    python graph_plotter.py
   
5. Output

    After execution, a folder named Graphs/ is created containing:
    
    Histogram of ratings
   
    Boxplot by genre
   
    Average rating bar chart
   
    Ratings trend over years
   
    Scatter plot
   
    Correlation matrix
   
    Pie chart of genres
