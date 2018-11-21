# AdHoc iOS Distribution Website Starter
[![Build Status](https://travis-ci.org/YouYue123/iOS-Adhoc-Distribution.svg?branch=master)](https://travis-ci.org/YouYue123/iOS-Adhoc-Distribution)

Instruction for creating end-to-end AdHoc distribution website(Chinese version) -- [Link](https://youyue123.github.io/tech/2016/12/14/use-Node.js-Bluemix-build-iOS-distribution-website.html)

## [Demo](https://sample-ios-distribution.au-syd.mybluemix.net/)

![image](https://s27.postimg.org/avzlqtipf/appdemo.png)

## Motivation

Distributing an iOS app is pretty painful in current world.

There are totally 3 ways to show your app.

  1. AppStore
  2. AdHoc
  3. Install directly with your Mac

Using [Appstore](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/SubmittingYourApp/SubmittingYourApp.html#//apple_ref/doc/uid/TP40012582-CH9-SW1) to distribute your app is the most common and recommended way but also very painful to wait for the reviewing.

Sometimes we just wants to show our app to friends and let them try first. You are not iron man and it will be quite hard to take your Macbook to visit every friends you want to impress.

AdHoc would be the best way for you to share your app with your friends.

## Pre-requirement

For AdHoc distribution, you need to sign your app using one of the following way.
  1. Enterprise Distribution Certificates
  2. Developer Distribution Certificates with [adding your friends UDID](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/MaintainingProfiles/MaintainingProfiles.html)

After signing your app, by following [this process](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html#//apple_ref/doc/uid/TP40012582-CH8-SW1), you will get an ipa file and a mainfest file.

## Usage
1. Download the starter code here
2. change config.js as yours
```javascript
const config = {
  APP_NAME: 'TestDistribution',
  WEB_URL: 'https://sample-ios-distribution.au-syd.mybluemix.net'
}
```
3.replace the ipa and mainfest file in folder APP/
## Issue
Feel free to give PR and issue comment
