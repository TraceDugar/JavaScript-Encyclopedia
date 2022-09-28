## Class 13 Reading Notes

**Local Storage**\

1. The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it.
If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side,
and you would check the user name to know which state to revert to. But what if you don’t want to force people to sign up?
This is where local storage comes in. You would keep a key on the user’s computer and read it out when the user returns.

2. Of course, any powerful technology comes with the danger of people abusing it for darker purposes. Samy, the man behind the “Samy is my hero” MySpace worm, recently released a rather scary demo called Evercookie, 
which shows how to exploit all kind of techniques, including local storage, to store information of a user on their computer even when cookies are turned off. This code could be used in all kinds of ways, and to date there is no way around it

3. Use Case #1: Local Storage Of Web Service Data #
One of the first uses for local storage that I discovered was caching data from the Web when it takes a long time to get it. My World Info entry for the Event Apart 10K challenge shows what I mean by that.

When you call the demo the first time, you have to wait up to 20 seconds to load the names and geographical locations of all the countries in the world from the Yahoo BOSS Premium Web service. If you call the demo a second time, there is no waiting whatsoever because — you guessed it — I’ve cached it on your computer using local storage.
You can see the difference in loading times in the following screencast:

The code for the world info is available on GitHub.

This can be extremely powerful. If a Web service allows you only a certain number of calls per hour but the data doesn’t change all that often, you could store the information in local storage and thus keep users from using up your quota. A photo badge, for example, could pull new images every six hours, rather than every minute.

This is very common when using Web services server-side. Local caching keeps you from being banned from services, and it also means that when a call to the API fails for some reason, you will still have information to display.

getJSON() in jQuery is especially egregious in accessing services and breaking their cache, as explained in this blog post from the YQL team. Because the request to the service using getJSON() creates a unique URL every time,
the service does not deliver its cached version but rather fully accesses the system and databases every time you read data from it. This is not efficient, which is why you should cache locally and use ajax() instead.

//-- source: https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/
