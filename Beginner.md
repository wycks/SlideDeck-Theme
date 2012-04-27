


*  Install WordPress without using the 5 min install

The first challenge is to install Wordpress on your local machine or remote site without using the famous 5 min install and without using the default wp_ database tables.

Use wp-config.php and manually entering the required info to connect WordPress to your database.
 
Log into admin

Hints: You will need to first set up a database in mySQL.

---------



*  Install the sample.xml

You should be up and running, the next step is to populate WordPress with soem default content. We are going to do the the same way WordPress exports and imports xontent, using and XML file. Open the sample.xml in your IDE and have a look at how it is formatted.

Use the sample.xml file and import it into WordPress

Browse the site.

Hits: To import it you got to tools-->import and click WordPress.


-----------

*  Debugging

Debuggin is crucial to development, and lucky for us WordPress already has some great tools to help us.

You turn on debugging in wp-config.php and it is highly recommend your install the debug-batr plugin.

Open the home page and find out how many db quries were made and the total query time.
Opne a page and find out what template it is using.

Hints: dont forget to turn on savedqueires, true.

---------------------

*  Create a child theme

Child themes are great because og bla bla bla. We will now do all theme editing in the child theme.

Create a child theme of twenty eleven, and activate it.

-------------------

*  Change some CSS

Change the post background-color to #grey.

-------------------

*  Change some HTML

Add a div somewhere like <div>Hello</div> (above title , delete in next step)

--------------
*  Change the title

We dont want some lame static html, lets alter the title of the blog. Add the descritpion too, using php.

--------------

*  Something with loop

Have a look at the loop, intro to the loop, just spit out  <div>Hello</div> as a loop example.
http://codex.wordpress.org/Global_Variables

We will come back to this later with a real example.

--------------------------


* What is a Template Tag

http://codex.wordpress.org/Stepping_Into_Template_Tags

---------------------

*  Page template

Create a new page template , and also some other template.

-----------------------

*  Body class/post_class/comment_class

Let add a body id and also a post id programatically.

Style 2 pages differantly.

------------------

*  Alter the main loop

Simple example to later the main loop with the amount or something, or category.
http://codex.wordpress.org/Separating_Categories

---------------

*  Something with functions.php

Something simple with title to show from previous example.

-----------------

*  Enqueue scripts  move this to intermediate?

javascripts and styles done right.

make a javascript and css file then enqueu them.