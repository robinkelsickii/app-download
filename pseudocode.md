# Downloading an app Pseudocode 

## Overall Goals 
1. To recognize which operating system that your phone operates on.
2. With the recognition of the operating system, decide which store to use in order to download the app.
3. Scroll through a landing page which features and recomends apps.
4. Switch between apps, games, books, and movies.
5. Switch between genres.
6. Switch between adult vs. Kids ratings.
7. Paid apps vs. free apps.
8. Top of the charts button.
9. Search inquiry so that a specific app can be found.
10. View and write reviews.
11. View amount of downloads.
12. View ratings for the game.
13. Learn about the developer and about the app itself. 
14. Find more apps by the developer or related apps to this one. 
15. Download the app. 

## Objects 

### Phone OS 
* Determines whether the *app store* or *play store* will be used.
* Apple phone will require using the **App Store** and Android will require the **Google Play Store**.

### Store Landing Page
 * Should allow you access different aspects of the store such as genres and types of apps.

### Search Bar 
* Allows you to input specific data that brings you to a page that lists relevant apps according to your search inquiry.

### App landing Page 
* Where you can view reviews, developer information, app information, and download the app itself. 

## Functions Based on Objects

### Phone OS
* getOs() => determines whether you have an Android or Apple Phone.
* openStore() => opens play store or app store respectively.

### Store Landing page
* onClick() => allows you to scroll and look through recommended and featured apps.
* selectGenre() => choosing a genre sends you to a page that shows apps based on the genre.
* appCategory() => allows you to select between apps, games, books, and movies and sends you to the respective page. 
* appAudience() => takes you to pages based on content ratings. Discerns between games made for kids and/or adults.
* appCost() => Determines whether the app is free or not and sorts between the two. 
* topApps() => shows the apps in order from best to worst based on average user rating.

### Search bar
* userInput() => allows user to input anything into the search bar field and it will return results that are related to the inquiry. 

### App Landing Page 
* writeReview() => If you have already seen the app you can write a review or you can just view what people say about the app.
* downloadAmount() => view only. This tells you how many people have downloaded the app. 
* devContact() => veiw contact info for the developer asuming that you have bugs to report, or if you just want to say hi. 
* relatedApps() => allows you to view apps similar to the page you are looking at. 
* downloadApp() => does what we came here to do. Extracts thhe files from the app store and puts it on your phone. 

## Pseudocode
### Determine which store to use

```
Start

// Funtion that gets the OS

function getOs() {
    If (os === android) {
        launch googlePlayStore
    }
    else if (os === ios) {
        launch appStore
    }
}
End
```
### Scroll through store landing page

```
Start

recomended.apps onClick() => opens a page that shows apps based on ones that you have downloaded in the past.

featured.apps onClick() => shows the apps that have gotten downloaded the most and reviewed the highest in the last x amount of days. 

medium.app onClick() => lets you choose between books, apps, games, and movies and displays apps pertaining to that particular medium.












