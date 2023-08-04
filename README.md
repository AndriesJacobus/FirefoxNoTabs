# FirefoxNoTabs
userChrome.css to hide the top tabs bar for Firefox with instructions. Useful when you have a side tabs extention or just want a cleaner look and feel.<br/>
Note: this will only hide the tabs bar at the top, not the URL navigation bar, or the window icons.

# Instructions

## Adding the userChrome stylesheet to your Firefox Profile
1. Open Firefox and in the URL tab enter: `about:profiles`
2. Find the default profile for your machine. Under the row `Root Directory`, click the button to open the profiles folder directory. Now you should see all your profiles as folders
3. Open your default profile folder inside your root profile directory (called something like `e3w6q1zc.default-release`)
4. Find the `chrome` folder. If one doesn't exist, create one
5. Find the `userChrome.css` file. If one doesn't exist, create one
6. Make sure your `userChrome.css` file looks the same as the `userChrome.css` file in this repository
7. Save the `userChrome.css` file and close the file explorer

Next you have to add the permission for Firefox to utilise the `userChrome.css` Stylesheet.

## Adding the Stylesheet permission
1. Open Firefox and in the URL tab enter: `about:config`. Click `Accept the risk and continue` permission
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and make sure it's set to `true`
3. Completely close Firefox and start it again. Now the tabs bar at the top should be hidden