# gap-coder-execution
A small HowTo

In IOS you can install app http://www.gapcoder.com/ and use that for test-running a Cordova app.

Enter credentials. In the app :
* Enter Hosting Providers - GitHub
* SSH Transfers: Off
* Enter Username, Email and Password

Create a Cordova app. In GitHub:
* Create a Cordova project having confix.xml in the root #required for being able to run in GapCoder
* Content could be like this project: https://github.com/gapcoder/cordova.git
* or other hybrid cordova frameworks as compared here: https://www.airpair.com/ionic-framework/posts/hybrid-apps-ionic-famous-f7-onsen

Import the app to GapCoder. In the app:
* Press "+"
* Clone from GitHub
  * Name: Whatever you like
  * Path: https://github.com/gapcoder/cordova.git #remember to write https:// before github.com

Run the project. In the app:
* Open the project
* press the Play-button

Push or Pull. In the app:
* Edit some code
* Go back root of project
* Press Menu-button
* Commit & Push

The End.
