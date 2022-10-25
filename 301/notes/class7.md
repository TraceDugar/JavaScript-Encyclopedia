## Class 7 Reading Notes & Keys

1.**Who is Roy Fielding?**
*He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.*
<br>

2.**Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?**
*Because they weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.*
<br>

3.**What is the HTTP protocol that Fielding and his friends created?**
*For anything really. That guy, Roy Fielding, he talks a lot about what those things point to in that research I was talking about. The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”, which is what those things point to.*
<br>

4.**What does a GET do?**
*For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

Web pages usually have images, right? Those are separate resources. The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.*
<br>

5.**What does a POST do?**
*f one system needs to add something to another system, it would use an HTTP verb of POST.*
<br>

6.**What does PUT do?**
*If a system wants to replace something in another system, it uses an HTTP verb of PUT,*
<br>

7.**What does PATCH do?**
*or, to do a partial update, it'll hopefully use PATCH.*
<br>

# API KEYS

Geocoding: Yes
Weather: Yes
Yelp: Yes
Movie DB: Yes
