/* he first part of this code should check for the OS to know which store to use. We will use two OS*/

variables:
macOS and android

// create a function that checks the OS to open the correct app store.

function getOS() {
    IF macOS {
        open appStore
    }

    IF android {
        open the googlePlayStore
    }
}

/*You can scroll through recomended options on the front page of the store or you can input exactly what you want to find.*/