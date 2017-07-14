# iOS App Creation Steps through ionicFramework

#### INTRODUCTION
This repository serves as personal notes on the steps required to create iOS
apps through ionic Framework.  
The steps are grouped as follows:
* Development Steps
* Provisioning Steps

#### REQUIREMENTS
You will need the following to complete the task:
* OpenSSL (to create CSRs and keys)
* Development environment:
    * Ionic Creator Account (if you want to develop through the cloud) or
    * Simply install the following and start developing from your machine:
        * [Node.JS](https://nodejs.org/en/)
        * [Ionic](http://ionicframework.com/)
        * Cordova (for native functions implementation)
        ```command-line
        npm install -g ionic cordova
        ```
* Apple Developer Account ($99/yr) obviously to upload and test your application
* Good text editor
    * Atom
    * Brackets
    * Notepad++
* Mac Machine (or Mac Virtual Machine ;)), to load your IPA into developer account and test on iOS Simulator
* Android Stuff for Android deployement and testing
    * [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html)
    * [Android Studio](https://developer.android.com/studio/index.html)
    * [Updated Android SDK tools](https://developer.android.com/studio/intro/update.html)
* Splash Screen and Icons

## App Development Stage
Here are the steps to start developing your app
* For Typescript backend `ionic start yourprojectname tabs`
* For JavaScript backend `ionic start yourprojectname tabs –type ionic1`
  (for JS support, ionic 2 is strictly Typescript and most of us hate that)

#### Tips for App Development Stage
These are some tips that you might or might not need while developing your application
* In development environment, while developing your API:
    * Use HTTPS for iOS as HTTP is not accepted.
    * add the following code to your PHP files to enable cross-origin requests:
    ```PHP
    header("Access-Control-Allow-Origin: *");
    ```
    * to start (test) your app `ionic serve`

## App Provisioning Stage
These steps are the minimum requirements for provisioning (for usage or testing) your app.
* Step 1
* Step 2

#### Tips and Tricks for App Provisions

## References
* [ionic Framework Docs](https://ionicframework.com/docs)
    * [ionic deployment manual](http://ionicframework.com/docs/intro/deploying/)
* [AngularJS Basics](https://www.w3schools.com/angular/default.asp)
* [AngularJS Docs](https://docs.angularjs.org/api)
* []()
* []()

## MAINTAINERS
#### Current Maintainers:
* **Mohannad F. Otaibi** (@buFai7an) - http://www.mohannadotaibi.com
* **Your name?** - email me at mohannadotaibi + gmail.com

#### Sponsored by:
* 6 Degrees Technologies - http://www.6d.com.sa  
  Specialized in, simply, Technologies.

## COPYRIGHTS
No copyrights at all, I just collected all of this from all over the internet (which is a public place) and published it here for my own use and for your use.
