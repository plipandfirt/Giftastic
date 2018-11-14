## GifTastic

## Overview
In this assignment, I used the GIPHY API to make a dynamic web page that populates with gifs of your choice. To finish this task, youThe app calls the GIPHY API and use JavaScript and jQuery to change the HTML of your site.

## GIPHY Notes:

Like many APIs, GIPHY requires developers to use a key to access their API data. To use the GIPHY API, you need a GIPHY account (don't worry, it's free!) and then obtain an API Key by creating an app.

The protocol in the query URL from http to https, in order to make the app work properly when deployed to Github Pages.

An array of strings was created, each one related to a topic that interests me. It was saved to a variable called topics.

The app should takes the topics in this array and creates buttons in the HTML.

A loop that appends a button was used for each string in the array.
When the user clicks on a button, the page grabs 10 static, non-animated gif images from the GIPHY API and places them on the page.

Under every gif,  a rating is displayed (PG, G, so on). This data is provided by the GIPHY API.

A form was then added that takes the value from a user input box and adds it into the topics array. Then makes a function call that takes each topic in the array remakes the buttons on the page.

## Deloyed site
https://plipandfirt.github.io/Giftastic/

