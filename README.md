# CS411 Project

## Contributors
* Justin Ingwersen
* Rebecca Arce
* Ali Kinay
* Tyler Correll

## Project Ideas

* Workout Song Sorter -JogSort

Application that organizes songs in an order that fits the user's workout routine intensity. The app will sync with the user's Spotify account, pull in songs from playlists, and sort them depending on the intensity of the workout, which will be determined by the user. The user will also create tags (a playlist for a specific exercise) to determine which songs should be played during certain workout times/activities. For example, if the user is going for a light jog with sporadic sprints, during the jog the app will pick songs from their jog tag and when it's time for the user to start sprinting the app will change to their sprint/running tag. 
The user will also need to log in some personal information when they start using the app, such as their age and what activities they usually do, and they will be given the option to log onto Facebook/Twitter and share their tags with their friends. 
The app will also be able to recommend different songs based off the user's favorite artists/songs (some API database).

* Clothing Combinator 

A web application that uses current fashion trends to suggest clothing advise. Users will be able to login to their account and upload photos of their clothes. The app will then, recommend clothing mix and match options based on popular fashion news/trends that are online. Additonally, users will have the chance to specify region/age/sex and add tags to personalize their profile and get the most accurate results. On the background the application will utilize mutliple API's in getting feeds about fashion trends and determining the context (color, texture, size) of the uploaded photos of clothes to make mix and match. The app will also allow users to find popular clothes from other website by presenting links. 




## App Use Cases

* Jog-Run

A user opens up our website for the first time and is immediately promted to either "register" or "sign in". Since it is their first time they click on "register" and put in their basic information (name, age, height and weight). After they register there is a page that asks if they want to log in with Spotify. The user is then redirected to the main page where they get to choose between "manage tags" and "start exercise". 
In "manage tags" they would pick between running, jogging and lifting where they would then be redirected to a page to add songs from their spotify playlists to each of these exercise tags.
In "start exercise" they would add their exercises in order and input how long each of those exercises will last. They will also have an option called "cut songs" that would skip the song if the exercise changes mid-song. After they're done they can click on "start exercise". There will be a 3 second count down and then the app will create a playlist for their workout. This will include songs from their spotify playlists and some recommended songs (using API).
The user can end the workout at any time. When the workout is over the app is redirected to the main page.


