Max/James/



What is middleware, and whats a useful example?

Middleware is code that performs operations on a request or respone, then calls the next function.  A useful example might be 
body parser to read data from user input forms.

What are the HTTP verbs and what's the difference between them?
GET-Get retrieves info from the browser
POST-Sends information to servers and a database
PUT-update existing data
DELETE-remove data

Describe the two patterns of asynchronous functions- callbacks vs async await.

A callback function needs parameters for the database query name and an error. it will then run the code defined in the callback.
An async function handles the errors differently by asking the reader to try to run some code and if it throws an error it catches it in the error catch.


What is a model and what does it help us do?
A model is an object that sets the way input is received from the browser.  The keys and values are matched to the database.

What is session?
A seesion allows a users login info to be stored so a new login is not required when
the user changes pages within the app. This information is stored server-side.

I'm getting an error from my template- cannot read 'name' of undefined. What should I check and where?
Check GET route to make sure database information is being rendered.

I'm getting an error- "cannot cast to ObjectId for value 'new' at value '_id' for model Review". What the heck does that even mean???
"new" is not a valid ObjectId


Describe the necessary parts of a form to properly submit to our server. What are some common things to forget or do improperly that will result in bad responses/data? 

Input types with names that match the keys in the model, a proper action path, a PUT route in the controller, a submit button.  Forgetting any of these will give a bad response.



Tell your 5 year old cousin how the internet works.
Your computer can connect to other computers, kind of like the way you call somoenoe
 on the phone, and the other computers can send back stuff to your computer, like pictures or videos.


ALGORITHM CHALLENGE: 

In a seperate javascript file, write a LinkedList that works as a priority queue- when you add a new node to the list, it is given a number and finds its spot in line based on that number. Your linkedlist should have the following methods:

add(data, priority)
search(data)
remove() -> remove the head node from the list.
