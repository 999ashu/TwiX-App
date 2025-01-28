# TwiX App

## Description
### TwiX is a microblogging app. The key feature is the ability to add up to 3 emojis to a post, describing the user's mood and adding expressivity to their thoughts.

## Features and technologies
*Auth flow is implemented in `SwiftUI`.
* Other parts of the application are done with `UIKit`.
* The application supports anonymous users and email authorization, which is connected to the `Firebase Auth` service.
* Users can customize their profile information, share posts, and rate other people's posts. All information is saved in the `Firebase Firestore` NoSQL DB.
* Users can open other people's profiles from the feed or search for them in the search section. Profiles have implemented filtering of entries by those posted and liked by the profile owner.

## Demonstration
![showcase](https://github.com/999ashu/TwiX-App/blob/main/showcase.gif)
