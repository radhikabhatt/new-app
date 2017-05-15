# README

This application uses the following:

* Ruby version - 2.3.3

* Rails version - 5.0.2

* Database - Postgresql

Following these steps to start the application:

* bundle install

* rake db:setup

* rails s


Flow of the application:

* On running the application, you will see a login screen. I have created a dummy user in the setup steps. You can use these credentials to signin:

Username: testmax@mailinator.com
Password: Password123

Or you can create a new user using the signup link.

* The home page has a button called "Get Started" on clicking which, the test starts. The user has to select a option for every question and click next till the user ends the test. The user can navigate between questions using the 'next' and 'previous' buttons.

* Once the user finishes the test, he can view his score after the test.

* Once a user has finished a test, he can now see a 'Review' button on the home page. On clicking this button, the user can see in descending order of time, all the test he has taken in the past.

* Every test has a separate review button which shows the user what options he chose for all the questions asked in the test.