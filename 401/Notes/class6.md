## Class 6


(https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

Explain to a non-technical friend how you would safely hash and store a password.
I would use a hash algorithm, because they can store lots of data as quickly as possible, and hashing is the greatest way of protecting passwords.
<br>

What is Bcrypt?
crypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.
<br>

Why might you use something like Bcrypt?
For key stretching
<br>


(https://en.wikipedia.org/wiki/Basic_access_authentication)
What is Basic Authentication?
In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.
<br>

What properties are necessary in the header of a Basic Auth request?
Because the BA field has to be sent in the header of each HTTP request, the web browser needs to cache credentials for a reasonable period of time to avoid constantly prompting the user for their username and password. Caching policy differs between browsers.

HTTP does not provide a method for a web server to instruct the client to "log out" the user. However, there are a number of methods to clear cached credentials in certain web browsers.
<br>

How are username:password in Basic Auth encoded?
WWW-Authenticate: Basic realm="User Visible Realm"
<br>


Define the authentication process to a non-technical recruiter.
Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.
<br>

How should your error messaging respond (both HTTP and HTML)? Why?
The account registration feature should also be taken into consideration, and the same approach of generic error message can be applied regarding the case in which the user exists.

The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

It is interesting to note that the business logic itself can bring a discrepancy factor related to the processing time taken. Indeed, depending on the implementation, the processing time can be significantly different according to the case (success vs failure) allowing an attacker to mount a time-based attack (delta of some seconds for example).
<br>
