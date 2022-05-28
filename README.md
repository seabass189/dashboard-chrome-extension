# Dashboard Chrome Extension
 Anytime a new tab is opened in the Chrome Browser, a dashboard will appear on that new tab. This dashboard includes information like the time, the local weather (if location services are accepted) and data on Dogecoin. This is all displayed on a nature themed background image. 
 
 The background image is a random image from the Unsplash API and includes the photographer in the lower left corner. The Dogecoin information comes from the Coin Gecko API. The local weather data comes from the Open Weather Map API.
 
 This extension uses JavaScript, HTML and CSS. It includes the use of three different APIs and using async JavaScript. I had to sift through the documentation in order to find the information that I needed to pass to the API in order to get the desired data back.
 
## Want to run the extension? Choose one of the following

### Add to your Google Chrome web browser
Create a folder on your computer with the following files:
- icon.png
- index.css
- index.html
- index.js
- manifest.json

Go to your Google Chrome Extensions page and click on the "Developer Mode" toggle on the right. Click the "Load Unpacked" button on the left, navigate to the folder containing the files and click "Select Folder". The extension has now been added! Open a new tab, allow the extension to use your location and keep the changes that it makes.

Reference: https://www.freecodecamp.org/news/building-chrome-extension/#manifest-json-file
 
### Use Visual Studio Code with the "Live Server" extension to run the web application
Extension: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

Tutorial: https://youtu.be/y4qqQeUDCBQ?t=53
