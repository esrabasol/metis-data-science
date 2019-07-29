# metis-data-science
Google Play Store Apps

1. What is the question you hope to answer?
I hope to predict whether a new app will be downloaded in Google Play store

2. What data are you planning to use to answer that question?
I am planning to use web scraped data of ~10k Play Store apps.

3. What do you know about the data you're using so far?
The data consists of 2 csv files:

		• googleplaystore.csv : details of the applications on Google Play. 
			App: Application name
			Category : Category the app belongs to
			Rating : Overall user rating of the app (as when scraped)
			Reviews : Number of user reviews for the app (as when scraped)
			Size : Size of the app (as when scraped)
			Installs : Number of user downloads/installs for the app (as when scraped)
			Type : Paid or Free
			Price : Price of the app (as when scraped)
			Content:  RatingAge group the app is targeted at - Children / Mature 21+ / Adult
			Genres : An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
			Last : UpdatedDate when the app was last updated on Play Store (as when scraped)
			Current : VerCurrent version of the app available on Play Store (as when scraped)
			Android Ver : Min required Android version (as when scraped)
  	• googleplaystore_user_reviews.csv : This file contains the first 'most relevant' 100 reviews for each app. Each review text/comment has been pre-processed and attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity.
			App: Name of app
			Translated_Review: User review (Preprocessed and translated to English)
			Sentiment: Positive/Negative/Neutral (Preprocessed)
			Sentiment_Polarity: Sentiment polarity score
			Sentiment_Subjectivity: Sentiment subjectivity score

4. Why did you choose this topic?
It gives opportunities to:
	• Analyze deeply the Android market and detect potential new apps. 
	• Apply various prediction methods on the data and compare them.
	• Reprocess user reviews at the user review file and try to increase the review sentiment info. (if I have time)



