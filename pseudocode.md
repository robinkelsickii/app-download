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

/*At this point whether you click on the app name or input the name and find the app that way you will come up to the main app screen*/