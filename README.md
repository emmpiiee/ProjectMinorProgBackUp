# ProjectMinorProg

## Summary app
This app is a new kind of social media. Celebrate your event with all your guests closeby. The app is a way to capture guest photos and keep your guests up to date. 

### Problem
Chasing down photos after an event that you organized is a hassle that most of us have experienced. You want all the photos that are made during the day in one album, also the photos your guests made. From now on this is possible with this app. Let all your guests post pictures and comment on pictures other guest made. You can like pictures of others and have an timebased wall of photos you and your guests posted. 

### Features
- option to let your guests sign in to the group (MVP)
- option to let your guests see the photos posted (MVP)
- option to let your guests post photos (MVP)
- option to like photos and comment on photos other guests posted (Option)
- option to let your guest make photos directly in the app
- option to have a profile with information about guests (also a picture that shows guests) (Option)

### Data
No external datasets will be used for this app. We'll make our own database for the photos. This we will extract using JSON and Swift.
More information in the sub API

### Parts App
Seperate parts of the app can be defined. 
- You'll need a login to the correct wedding and login to your account (maybe using facebook) with a certain security so not anyone can log in your account
- You'll need an option to make photos or add existing photos from your library to the wall
- You'll need an option to see the wall with all the posted photo's 
- (optional) You'll need an option to change you're profile and see all your posted photos
- (optional) You'll need an option to see other the profile and the pictures other guest posted.

### API
We need to create our own online database, which can handle the size of a photo. The API of dropbox will fullfill this whish. 
We need to make it possible to extraxt and push photos to the online database. 

### Difficulties

### Similair applications
- It's an instagram like app, only in instagram it's not possible to make groups and add photos to a group and only people in that group can see it.
