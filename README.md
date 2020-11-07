# Amazon-fashion-recommender-
This is a recommender system which recommends fashion products to users based on the product they're currently browsing

We took 2 approaches here which is the NLP method where we did all text based featurizations and tasks and recommended based on that and the other was using computer vision through CNNs At the end, we can store these recommendations on a set dataframe(to avoid duplicate recommendations) and then select the top 5-10 and show it to the customer

This was a content-filtering based recommender system and not collaborative since we had the data about the title, picture, brand etc

For collaborative-filtering, we need user-data and item data to form user-user and itme-item similarity matrix for Matrix Factorization.

This user-data isn't shared by companies and is protected very well

At the end, to see how the model is performing , there is no loss function like the supervised learning techniques but we can perform A/B testing which will give us some solid feedbacks

The models here aren't the best it cold be because of restrains of my PC. Things like working with the entire 160k data and training the CNN on the whole data would just take too much time to execute and so the data was cutshort and there was a pre-trained modle loaded
