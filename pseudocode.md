/*The first part of this code should check for the OS to know which store to use. We will use two OS*/

variables:
macOS and android

//create a function that checks the OS to open the correct app store.

function getOS() {
    IF macOS {
        open appStore
    }

    IF android {
        open the googlePlayStore
    }
}

/*You can scroll through recomended options on the front page of the store or you can input exactly what you want to find.*/

Display recommendedApps
Input specificAppName

/*At this point whether you click on the app name or input the name and find the app that way you will come up to the main app screen which will have some information.*/

//These are all view only and you can look at them to find more information about the app.

appReviews
//You can look at what people think about the app
appInfo
//Tells you what the app is about.
appScreenshots
//pictures taken of the app functions
developerInfo
//ways to contact the developer should there be any bugs.

//Here are the parts you can actually interact with:

downloadApp
//lets you put the app on your phone for use.
writeReview
//allows you to share what you think about the app.
relatedApps
//shows apps that are similar to the apps you're looking at.

display appReviews
//displays app reviews
display appInfo
//displays "about this app"
display appScreenshots
//show screenshots from the app.
display developerInfo
//allows you to see the dev's contact information

onClick downloadApp
getInput userReview
onClick go to relatedApps

//At this point if you click download. The app should be on your phone. 