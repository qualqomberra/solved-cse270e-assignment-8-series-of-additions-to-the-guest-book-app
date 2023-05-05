Download Link: https://assignmentchef.com/product/solved-cse270e-assignment-8-series-of-additions-to-the-guest-book-app
<br>
In this assignment will make a series of additions to the guest book app from Chapter 3.

Copy over the guestbook app from chapter 3 to your nodejs working directory. Remember this is NOT to be in /var/www/html but rather in /home/ubuntu. It should be in your UID-270e-node git repository.

Create a directory called Assignment8 inside your working copy.

Put all the code in this directory.

Create a view called about.ejs. In this view place the following in an unordered list:

your name The course

The date

The Assignment

Modify the data form in the views.

Add a new input box (use type &lt;input type=”text”)

Use the id and name of “name”

Modify the label to have it reflect fact you are asking for the name.

Modify app.js

Modify app.js to store the new form filed in entries array

Modify index.ejs

Modify index.ejs so that after it displays the body of the guest book entry it shows who wrote the entry.

Add a clear function

Add a new handler for the get parameter “/clear”.

When invoked in app.js this code should clear the data by the following:

entries = [];

app.locals.entries = entries;

Modify the footer so it has three small bootstrap buttons that go to Main, about and clear.

&lt;a href=”/clear” class=”btn btn-primary btn-sm&gt;Clear&lt;/a&gt; is one button

The server should be running on port 3008 and should be running until I grade it.