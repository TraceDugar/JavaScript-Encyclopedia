## Class 12 Reading notes

**Status Codes Based On REST Methods**

1. **In your own words, describe what each group of status code represents**
<ol>
<li>100’s = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.<li>
<li>200’s = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.<li>
<li>300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.<li>
<li>400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.<li>
<li>500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.<li>
</ol>
  
2. **What is a status code 202**
*202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.
<br>
 
3. **What is a status code 308?**
*308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.*
<br>
 
4. **What code would you use if an update didn’t return data to a client?**
*204 No Content - The most fitting status code for this case. It’s better to reduce traffic and simply tell the client the deletion is complete and return no response body (as the resource has been deleted).*
<br>
 
5. **What code would you use if a resource used to exist but no longer does?**
*410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.*

<br>
 
6. What is the ‘Forbidden’ status code?**
*403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.*
<br>
 
 //----source: https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/
  
1.** Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
*
<br>
 
What is middleware?**
*
<br>
 
What does app.use(express.json()) do?**
*
<br>
 
What does the /:id mean in a route?**
*
<br>
 
What is the difference between PUT and PATCH?**
*
<br>
 
How do you make a default value in a schema?**
*
<br>
 
What does a 500 error status code mean?**
*
<br>
 
What is the difference between a status 200 and a status 201?**
*
<br>
 
 //----source: https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw
