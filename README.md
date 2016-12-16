#About

Steven Universe Fan site built with Drupal 7 as part of self study following Epicodus curriculum.  Paired with LawlietBlack.

# Instructions:

1. Download Drupal version 7.51

2. Replace the sites folder with the enclosed sites folder

3. Import the Database Dump

  a. Open phpMyAdmin and click on the "Import" tab.

  b. Leave all the default settings and make sure the character set is "utf-8"

  c. Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file we included in our sites/db-backup folder. It's okay to leave it zipped.

  d. Then click the "Go" button on the bottom left.

4. Create the Database User (not needed if using Acquia Dev Desktop)

  a. Lastly, we must recreate the database username/password that Drupal uses to store things in the database. We do this the same way we did when we created the database.

  b. After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

  c. Use the same username and password from before. (If we have forgotten what that was, we can always find that information in settings.php, or in the PDO Exception error message we saw displayed in the browser.)

  d. After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.

#User Stories
1. As an anonymous user I can see most of the site's content including the welcome page, the home page, the fan art gallery, cookie cat's page, and several articles. 

2. As an anoymous user I can see comments, but cannot post comments. 

3. As an authenicated user I can post comments. 

7. As a VIP I can edit my own comments. 

4. As a weirdo I can create new articles. 

5. As a weirdo I can edit and delete my own content. 

6. As a weirdo I can use easy social.

7. As a weirdo I can use the admin toolbar.

###Greetings Module
 1. As an registered user I can see a custom greeting based on my highest user role when I login

 2. 1. As an registered user I can see a custom farewell based on my highest user role when I logout

###Pet Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can view a page about a pet (Steven's Lion).  On this page I can see some basic details, a picture and a link to learn more information about the pet.  

###Cards Module
 1. As a anonymous or authenicated user I can access this module. 

 2. As a user I can vist /cards/name to see Hello + Name displayed on the page. 

###Title Case Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can enter a non- case sensative sentence into a form. 

 3. As a user, I can see my sentence in Title Case format. 

###Queen Attack Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can select the x and y coordinates (1-8) for both the queen, and target chess pieces from a drop down menu.

 3. As a user I can see if the queen is able to hit the target based on standard chess rules. 

 4. If both sets of cooridnates are the same, I will see a form errror message, since the two pieces cannot start on the same square in chess. 


###Rock Paper Scissors Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can enter in 'rock', 'paper', or 'scissors' in a form labeled player1.  

 3.  As a user I can enter in 'rock', 'paper', or 'scissors' in a form labeled player1, on a seperate page.

 4. As a user if I enter something other than 'rock', 'paper' or 'scissors' I will see a form error message, since those are the only 3 options for the game. 

 5. As a user I can see which player wins rock, paper, scissors and which choice each player made. 

###Ice Cream Poll Module
1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

2. As a user, if I enter a State in a format other than 'Oregon', 'oregon', 'OR', 'or', I will see a form error message asking me to enter a valid state.

3.  As a user, if I enter a flavor of ice cream, containing characters other than alpha characters and spaces, I will see a form error message asking me to use only alpha characters and spaces. 

4. As a user, I can see a message saying my vote for my flavor choice in my state has been submitted. 

###Sum Two Numbers Module
  1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

  2. As user I can sum two values together between -9,999 and 9,999. If I enter numbers outside of this range I will get a form validation error. 

###Triangle Tracker Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can enter 3 numbers, one for the length of each side of a triangle. 

 3. As a user, if I enter anything but a postive interger, I will see a form error message asking me to enter a postive interger. 

 4. As a user, I can see what type of triangle my measurements would make.

###Ping Pong Module
 1. As a anonymous or authenicated user I can access this module from the nagivation menu. 

 2. As a user I can enter a number, I would like to count up to. 

 3. As a user, if I enter anything but a postive interger, I will see a form error message asking me to enter a postive interger. 

 4. As a user, I can see a list of numbers, up to the number I selected, that replaces numbers divisble by 3 with 'ping', numbers divisible by 5 with 'pong' and numbers divisble by both with 'ping-pong'


#What I learned from this project
1. I learned how to make custom modules.

2. Praticed creating basic and custom content in drupal. 

3. Praticed making multiple user roles and setting permissions.  

4. Praticed using several common modules including: view, css injection, comments sweaver and contact.

5.  Praticed using themes 

6. Learned how to create and use forms in drupal, including element validation. 

#To Do
Figure out Cookie to store user role to present custome logout message based on user role

Add character bio pages for Gems, Steven, Greg and Connie

