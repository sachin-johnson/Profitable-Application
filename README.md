# Profitable Application Profile

The aim of the project is to conduct market testing in order to determine the genre of application that is going to be the most profitable in both iOS and Android application store. This analysis is to be used by developers to create a profitable application.

Since most popular applications are free of cost and makes most of its revenue form in-app advertisements, we will focus on this area for further analysis. The measure of profitability is directly influenced by the number of users in the application and their corresponding engagement with advertisements.

## Input data sets

There are over 2.2 million iOS apps available on the App Store and 3.4 million Android apps on Google Play. Most of these applications doesn't have enough users for further analysis, so we'll try to analyze a sample of most popular applications on both stores.

* `googleplaystore.csv` data set contains data on approximately 10,000 Android apps from Google Play. The data was collected in August 2018. You can download or view the data set using the following [link](https://www.kaggle.com/lava18/google-play-store-apps).

* `AppleStore.csv` data set contains data on approximately 7,000 iOS apps from the App Store. The data was collected in July 2017. You can download or view the data set using the following [link](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps).

## Data Cleaning

* Deleting incorrect data.
* Removing duplicate entries.
* Removing Non-English Apps.
* Removing Non-Free Apps.

## Data Analysis

As mentioned in the introduction, our aim is to determine the kinds of apps that are likely to attract more users because our revenue is highly influenced by the number of people using our apps.

To minimize risks and overhead, our validation strategy for an application idea is comprised of the following three steps:

* Build a minimal Android version of the app, and add it to Google Play.
* If the app has a good response from users, we then develop it further.
* If the app is profitable after six months, we also build an iOS version of the app and add it to the App Store.

Because our end goal is to add the application on both the App Store and Google Play, we need to find app profiles that are successful on both markets. For instance, a profile that might work well for both markets might be a productivity app that makes use of gamification.

### Most common genre
On analysis we found that the App Store is dominated by apps designed for fun, while Google Play shows a more balanced landscape of both practical and for-fun apps. This may not give the most popular genres, as they may not have the most number of users.

### Most popular apps by genre
One way to find out what genres are the most popular (have the most users) is to calculate the average number of installs for each app genre. We will eliminate few widely popular apps in each genre as they can be considered as an outlier. 

> `Games` is the best genre for an application profile in both Free-English iOS and Android store.

## Conclusion

In this project, we analyzed the data from both iOS and Android application store, with the goal of recommending an application profile that can be profitable in both markets. Gaming is the most popular category in both Android and iOS store by the following two criteria.

* By the number of applications present in store for each category.
* By the number of users in each category.

Initial assessment that the gaming category was oversaturated with more apps doesn't hold true, as the number of users are equally high for this category. So Games can be a good genre for a profitable application profile.
