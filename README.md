# Spotify songs recommendation system 
## Machine Learning Project on Spotify Recommendation System using Python
#### Spotify is the perfect example of the rise of music streaming services. The success of an app depends a lot on the user experience that the app provides to its users. A recommendation system is what helps a streaming application in providing a good user experience. So we can say that the Spotify recommendation system has played a major role in providing a good user experience which has resulted in such success for Spotify
#### To create a Spotify recommendation system, I will be using a dataset that has been collected from Spotify. The dataset contains over 175,000 songs with over 19 features grouped by artist, year and genre
#### Here is the dataset for your reference https://drive.google.com/file/d/1it3VAYze6nChmaxPHF3QLJcvoZhMsemQ/view?usp=sharing 
## Data Exploration
#### Let’s explore some key insights from this dataset so that we can select the best features for creating the recommendation system using "data.info()"
#### Then check the null values "data.isnull().sum()"
#### Now let’s have a look at the correlation between the feature. Here I will drop some columns such as ‘id’, ‘name’, ‘artists’, ‘release date’, and ‘year’ as these columns do not contribute much to the features of a song
#### Then drop the unneccessery columns "df = data.drop(columns=['id', 'name', 'artists', 'release_date', 'year'])"
#### "df.corr()"
## Data Transformation
#### Now I will normalize the dataset by using the MinMaxScaler method provided by the Scikit-learn library in Python
#### Songs of different genres may have similar characteristics which may affect the recommendation system. So I’m going to create a new feature here that will differentiate songs from different categories. For this task, I’ll use the K means clustering algorithm
#### Its easy to create a recommendation system for any music streaming application hope it will make sense 
# Thank you so much reading this any queries reach me on whatsapp +91 8825515505
