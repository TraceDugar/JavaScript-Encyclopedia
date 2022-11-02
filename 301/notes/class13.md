## Class 13 reading notes

**CRUD Basics**

1. **Which HTTP method would you use to update a record through an API?**
*Togo is really adorable, maybe we should see him sooner! For us to reschedule the appointment for an earlier time we can use the corresponding HTTP method for updating your playdate with PUT. This replaces all current data of the target resource (Togo) with the uploaded content (new appointment time/date). The ‘id’ in the route is how the resource is targeted (Togo) to ensure we only update the specified appointment, while leaving any others we may have scheduled untouched.*
*The route for this PUT request — /appointments/:id.*
<br>

2. **Which REST methods require an ID parameter?**
*Put, Post, Patch, and Delete*
<br>

//----source: https://medium.com/geekculture/crud-operations-explained-2a44096e9c88

**Speed Coding: Building a CRUD API**

1. **What’s the relationship between REST and CRUD?**
*CRUD uses REST to communicate to tie everythhing together. They are very close to being the same thing.*
<br>

2. **If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**
<ol>
  <li>Set up the routes.</li>
  <li>Prep for testing (add retrievable data)</li>
  <li>Connect Database</li>
  <li>Set up functions</li>
  <li>Test those functions</li>
</ol>
<br>


//----source: https://www.youtube.com/watch?v=EzNcBhSv1Wo
