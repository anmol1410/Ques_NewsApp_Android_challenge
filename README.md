This is a sample News Reader app that is supposed to display news list and the details.
The first page displays news list, when one of the items is clicked, it is supposed to show the detail of the selected news.
Unfortunately, the app is build on a god pattern, which is not good.
Alsdo there is no scope for unit testing in such a code base, forget about maintaining and extending this code furthur.
Can you help to fix all the problems?

## Screenshots
The screenshot below shows how the app looks like:
![](http://i.imgur.com/GgEP7FM.jpg)
![](http://i.imgur.com/yAtzntJ.jpg)

## About the project
All the data is coming from the web endpoint.
The response contains a list of news items as well as URLs to the pictures associated with each story.

## Improvements to do and few identified bugs
1. The main logic is written in MainActivity, which is not a very clean way to construct an app. Can you help to improve it?
2. The way of fetching and  parsing JSON data is not very nice. For example, if one of the name/value is missing, it
can cause the app to crash.
3. The layout is only suitable for phones. Can you create an immersive tablet experience?

Can you help to make it better?
