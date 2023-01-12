# Class 34

(https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

Explain the difference between a query string parameter and a path parameter.
The path parameter defines the resource location, while the query parameter defines sort, pagination, or filter operations. 
<br>

What would our API URL with a path id parameter be given the following information:
http://our-site.com/api/v3/stuff/things
<br>

    Domain: http://our-site.com
    
    <br>
    
    v3
    
    <br>
    
    model name: stuff
    
    <br>
    
    id: things

<br>

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
The interface would allow the user to Create Records, Read records, Update records, and Delete records.
<br>

(https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

Describe how you would use middleware to implement basic and bearer auth.
I would have middleware for handling errors, handling authentication and authorization.
<br>

Describe the handshake necessary to implement OAuth.
The Client must acquire its own credentials, a _client id _ and client secret,
<br>
  
Describe how Role Based Access Control works to a non-technical friend.
Role base access control is software that only allows certain users to do / see certain things whenever useing software. For example, a manager at a company can update things read more things, than a regular worker.  The apropriate information acess levels are also dependant upon the role of someone at a company.  If I were an employee i could not look at another employess paystubs in the internal bookkeeping software, but i can acess my own, I also cannot do anything other than READ ONLY, accounting can update my information as events happen in real time and have acess to all employees pay stubs.  HR can delete acess control based upon employement status etc.

