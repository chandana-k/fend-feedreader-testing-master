Project: Udacity Feed Reader Testing Project  

Instructions to run the application:  
-Download the repository in your computer, unzip it and open index.html in your browser to see the working tests.  


Tests implemented:  
-'RSS Feeds: have URL' loops through each feed and ensures it has a URL defined and that the URL is not empty.  
-'RSS Feeds: have name' loops through each feed and ensures it has a name defined and that the name is not empty.  
-'The menu: is hidden by default' ensures the menu element is hidden by default.  
-'The menu: changes visibility' ensures the menu changes visibility when the menu icon is clicked. The test also accepts the menu to display when clicked and to hide when clicked again.  
-'Initial Entries: has an .entry element after loading' ensures that, when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.  
-'New Feed Selection: changes the content when new feed is loaded' ensures that, when a new feed is loaded by the loadFeed function, the content actually changes.  


Udacity's instructions:  
In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included Jasmine and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite.   


Technologies used:  
- Jasmine
- jQuery
- HTML5 / CSS3  

[Live project link](https://chandana-k.github.io/fend-feedreader-testing-master/)