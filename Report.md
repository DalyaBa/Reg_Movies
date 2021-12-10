<h1> Abstract: </h1>
Prediction of the correct IMDB gross is essential for the movie industry and decreasing market risk. The
success and failure of the movie depend on movie-related variables. Therefore, the goal of this project is to
create a machine learning model that will predict the US movies gross taking into consideration many features.
The features include IMDb rating, certification of movie, number of votes, release year, movie duration, and
metascore. Exploring data scraped from the IMDb websites to see which features affect the prediction the most.

<h1> Design: </h1>
The progress of this project will be as follows. First gathering data using web scraping but the data was so small 1k abservation and then we decided to choose another dataset from Kaggle 5k abservation , then exploratory Data
Analysis (EDA) will be performed on the data we gathered. Finally, preparing data to be used in different
regression models. In this project, we analyze the relationship between the target variable “Gross” and the
features “duration, num_voted_users, cast_total_facebook_likes, facenumber_in_poster, budget, title_year, aspect_ratio”.

<h1> Data: </h1>
The dataset used in this project was extracted from IMDb website. we traied dataset from Kaggle to match our needs
in order. There were 5000 movies with 28 features initially.
The dataset becomes almost 3000 records with 20 features after we have done some cleaning and feature engineering
on the original dataset.

<h1> Algorithms: </h1>
<h2> ● Feature Engineering: </h2>
1. Convert categorical features to dummy variables.
2. Subtracting interactive terms in order to make the feature more relevant. that solved the multicolinaerty in the columns.
<h2> ● Models:</h2>
We have explored many regression machine learning models
in order to choose the best for our case. The models are linear regression, K-fold linear regression,
Polynomial regression, Ridge regression,lasso regression and random forest. The data was splitted into 60 percent
training, 20 percent validating, and 20 percent testing. The model we selected was polynomial regression
with degree 2 and 3 because it shows the best score between all models.

<h3> Best Model: Polynomial regression with degree 2 and 3: </h3>
   - Polynomial Training Score: 0.54368493
   - Polynomial Testing score: 0.53247904
<h1> Tools: </h1>
<h3> ● Technologies: </h3> Jupyter Notebook, google colab, spyder, Python.
<h3> ● Libraries: </h3> Pandas, NumPy, Matplotlib, Seaborn, Request, BeautifulSoup, plotly, patsy, holoviews, hvplot, and Sklearn.

<h1> Communication: </h1>


<img width="1174" alt="download (5)" src="https://user-images.githubusercontent.com/74211933/145575376-6624f5b5-ad5e-4782-aa12-773bd05b508e.png">

<img width="1225" alt="download (6)" src="https://user-images.githubusercontent.com/74211933/145575432-f94b757d-a078-49f1-9dae-2c5d8573b7f6.png">

<img width="403" alt="download (8)" src="https://user-images.githubusercontent.com/74211933/145575468-28821f9d-01a5-4173-946b-1f3ac817e754.png">

![bokeh_plot (3)](https://user-images.githubusercontent.com/74211933/145575491-ce9bdf47-7612-43c3-9072-a740410a8038.png)

<img width="399" alt="download (7)" src="https://user-images.githubusercontent.com/74211933/145575538-a45bd6ab-83cd-4035-ad07-5abd19f391f1.png">

![bokeh_plot (4)](https://user-images.githubusercontent.com/74211933/145575652-0b684150-5472-4140-a283-84325a745cff.png)





