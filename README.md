rssFeed
=======

Implement web applications to render rss feed

There are three files in the project, one is php file and the other two are html file. The purpose of project is to create web pages to read and render rss feed. 
In the feed.html, I use google feed api to request feed from google and the response is json format data which contains feed item from "VODO ALL Works". In the php file, I use another way to retrieve rss feed by using php functions to get rss xml file and format it to json. 

After javascript get json data variable, the render function will get feed one by one and put it to html table markup. The HTML using jQuery hide functions to hide some unimportant item in the table and when mouse move over the item, the table will display details information automatically. 

When using php to converse XML to json, the json contains some embedded object in json data, so I use JSON.stringify in 'feedPHP.html' to convert them to string. This can be further improved by using recursive function to render embedded object or object data formatting.