# 📌 Networking App - World News

This app was developed as part of the **Android Basics: Networking** course, a module in the **Udacity Android Basics Nanodegree** program.

## 📖 Project Overview

The goal was to create an app that **connects to the Internet** to provide news articles on a topic of user’s choice. The goal is to create a News Feed app which gives a user **regularly updated news from the Internet related to a particular topic, person, or location.**

---

## ✅ Requirements Followed

The app must include the following:

•	Main screen which displays multiple user stories 
-	Each list item on the main screen displays relevant text and information about the story.
-	Stories shown on the main screen updates properly whenever new news data is fetched from the API.
-	Clicking on a story uses an intent to open the story in the user browser.
•	Connecting to an API
-	 App queries the content.guardianapis.com api to fetch news stories related to the topic using api key.
•	Parsing the JSON response 
-	The JSON response is parsed correctly, and relevant information is stored in the app.
•	Handling error cases gracefully
-	The app checks whether the device is connected to the internet and responds appropriately.
-	Shows appropriate message for a bad server response or lack of server response.
•	Updating information regularly 
-	When there is no data to display, the app shows a default textview that informs the user.
•	Using an AsyncTask
•	Doing network operations independent of the Activity lifecycle
-	Networking operations are done using a Loader rather than an AsyncTask.
•	Use Uri.Builder class to add query parameters to the URL


Screens of the App
This app contains Home Page, Settings page, About Us Page, Side Navigation Bar with various options
It features a beautiful and visually appealing UI design. The app's UI is fully responsive, adapting smoothly to various screen sizes for an optimal viewing experience across different devices.
Home Page – contains various news stories with share button. Tapping the card gives user pop up choice to open the user story in the browser.
Settings page – gives user choice to go with preferences
About Us Page – with some information
Side Navigation Bar – gives user option to view news story according to the users choice
