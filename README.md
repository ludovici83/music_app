# music_app
The main objective of this exam is to develop predictive models for users that upgrade to the premium version of a music streaming app, and to present differentiating initiatives, from a business perspective, to increase the subscription rate to the premium version.
There’re several approaches to get relevant conclusions, we’re interested in your process of reasoning and how you support your decisions. Please show all your work, invest a max. of 6-8hrs of your time. The tasks include data preparation, modeling, evaluation and presentation:
1. Data preparation
The data set is titled “Exam_music_streaming_app.csv”
The names of the columns are self-explanatory; In case of doubt, you will find at the end of this document a table with the names and description of columns. Make sure to cover, at least, the following points:
▪ Estimate which variables are potentially more significant for modeling, and generate a couple of relevant display
▪ Create a new categorical variable that groups the clients by the level of use of the app 2. Modelingandevaluation
When developing a model to predict users that upgrade to the premium version, select one of the following options and apply the 3 mentioned models:
a. Clustering model to choose + xgboost + Logit or probit regression
b. PCA + ensemble model to choose + Logit or probit regression
To evaluate the accuracy of the models, please define:
▪ Precision measurement
▪ Validation strategy to guarantee external validity
▪ Balance between false positive and false negative rates
Establish a comparison among the 3 models and determine the most significant variables for prediction.
3. Presentation
Prepare a short presentation (max 10-15 slides) explaining the data preparation, modeling and evaluation, use relevant visualizations (histograms, heatmaps, network visualization, i.a.).

￼
￼Assume that you must execute commercial initiatives with 500 users that are not subscribed to the premium version, and that these actions have a cost of 0€.
▪ How would you select those 500 target users?
▪ Suggest which initiatives would you implement, based on the profile of those 500
target users derived from your predictions
▪ If you could require additional information for your analysis, which variables would
include to maximize the results from a business perspective?
Annex
Column Description
User_id
￼
￼
Unique user identifier
Active_days
Number of days active during the last 365 days
Songs_per_day
￼
￼
Average number of songs played per day
Music_genres_per_day
Average number of music genres played per day
￼
Numer_devices
Number of devices where the application was used
Proportion_working_time
Proportion of hours at work using the app
￼
Searches_per_day
￼
Average searches per day
Proportion_popular_songs
Proportion of Billboard songs reproduced
￼
NORTH_AMERICA
User from North America
EU
User from European Union
￼
ASIA
User from Asia
￼
￼Premium_upgrade
User who has signed the premium version (Target variable)
