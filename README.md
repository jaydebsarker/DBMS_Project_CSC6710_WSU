# DBMS_Project_CSC6710_WSU

This is a course project. One can create account in this website and add their interested videos. 
You can search for new videos, add new ones. User can rate the videos (1 to 5 stars) and can search for top 
rated ones. Moreover, you can subscribe the city name and will be notified automatically if any new video will be uploaded for that specific city.
We have not hosted the website yet. You can read details how to run the project and full project description. 


Group Members Information:

Asif Kamal Turzo, email: asifkamla@wayne.edu
Jaydeb Sarker, email: jaydebsarker@wayne.edu

Follow the steps:

Before starting to run the project install and configure the following tools:
1. Install  Java JDK 13.0.1
2. Install MySQL Server on https://dev.mysql.com/downloads/windows/
3. Create a user name "john" and set password "pass1234". Create a database named:'sampledb'
4. Install Eclipse Oxygen EE from : https://www.eclipse.org/downloads/packages/release/oxygen/rc2/eclipse-ide-java-ee-developers
5. Download and install Tomcat 9 from: https://tomcat.apache.org/download-90.cgi
6. Set up as following: Window -> Preferences -> Server -> Runtime Environment, Choose Tomcat 9.0 in Eclipse
7. Use the library for connecting: 
  i. jstl-1.2.jar (used to HttpServlet, HttpServletRequest, and HttpServletResponse)
  ii. mysql-connector-java-8.0.13.jar  (connection to be established to the database)

All set. Now run the project by followings:

8. Import the csc6710_asif_jaydeb_part3.war file into Eclipse. 
9. Run the "homepage.jsp" from the web content in the server.


Here is the description of our project part by part and also assigned the name who did this: 


For Project Part 1:
(Done by: Asif Kamal Turzo)
Step 1: A "homepage.jsp" where there are two buttons. One is "sign in" and "sign up".

(Done by: Jaydeb Sarker)
Step 2: you will get Signin and Signup button. Remaining parts are organized as the requirement of the project.

(Done by: Jaydeb Sarker)
Step 3: If you click sign up button, it will show that you need to initialize your database. So log in as root by clicking Sign In button.

(Done by: Asif Kamal Turzo)
Step 4: You must put emailid as : "root" and password= "pass1234" as first log in for root. 

(Done by: Asif Kamal Turzo)
Step 5: After successfully log in as a root you need to intialize database by clicking the button "Initialize Database". 
        Some database tables are automatically created in the system and some data are inserted in that table.
        Then it shows database initialized. Then you can change your password.

(Done by: Jaydeb Sarker)
Step 7: If you are a new user, you need to sign up first in the "homepage.jsp".

(Done by: Jaydeb Sarker)
Step 8: For Signing up as a new user, you need to put all of your info according to the page. You have to consider two things for signing up:
           i.  your password and confirm password must be matched
          ii. your given email id must be valid
         iii. your email id must be unique for this system

(Done by: Asif Kamal Turzo)
step 9: after signing up, you can sign in as a user



For Project Part 2:
Follow the steps after following part 1 portion:

(Done by: Jaydeb Sarker)
Step 1: There is a new button "Search" in homepage for searching the video. Any registered or unregistered user can search the video in search page using city name or tag or semantics.

(Done by: Jaydeb Sarker)
Step 2: A user can upload new youtube video after sign in the page and click "Upload New Video" button. Then she 
        can find all the text field to upload the video. But she can not upload a video which has been uploaded already. 

(Done by: Jaydeb Sarker)
Step 3: Also, there is a restriction that a user can not upload more than 5 videos in a day.

(Done by: Jaydeb Sarker)
Step 4: Then after signing in,  a user can search the video by using city name or tags or semantics. 

(Done by: Asif Kamal Turzo)
Step 5: A registered user give review to the video from the search results. There is a button "Review" and user can click the button to give review.
        If that video was posted by her, she can not give review and she will get a message. Otherwise, she can give review and rate the video (0-5). 
        Also, she can give her comments of that video.

(Done by: Asif Kamal Turzo)
Step 6: A user can see also all reviews of that video after clicking the "review" button from the search page. 

(Done by: Jaydeb Sarker)
Step 7: A user can delete her own review but can not delete of others review. 

(Done by: Jaydeb Sarker)        
Step 8: After finding the video from the search page a user can also add that video to her favorite list by clicking "Add to Favorite" button. 

(Done by: Asif Kamal Turzo)
Step 9: Then a registered user see her favorite list after log in to the system and click the button "View Favorite List"
        She can delete her favorite list by clicking the button "delete from favorite". 

(Done by: Asif Kamal Turzo)        
Step 10: In search option, one user can find one or more videos. Then she can subscribe the video by clicking "Subscribe this city". 
        Then, if any registered user will upload a video of that city, that will be automatically add to her favorite list. 

(Done by: Asif Kamal Turzo)
Step 11: A user can search video either registered or not. Then she can give review/ add to favorite list/ subscribe after log in the system fromt he seach output page.


(Done by: Asif Kamal Turzo)
Step 12: Moreover, a registered ser can search the video after log in the system. Then he can do the above functionality.


(Done by: Jaydeb Sarker)
Step 13: A registered user can log out from the system by clicking log out button. 



Project Part 3:
This part is mainly for root after log in the system.
A root can do the followings by clicking those texts:

(Done by: Asif Kamal Turzo)
"What is cool": Only root can see the youtube videos which have a five star score.  

(Done by: Asif Kamal Turzo)
"What’s new": root can see the youtube videos that have been posted in the past 10 days. It will be showed from latest one first.  
              A registered user can also see this after login from her portal. The she can back to his own page by clicking the back button. (Done by: Jaydeb Sarker)

(Done by: Jaydeb Sarker)
"What's hot": root can see top 10 youtube videos that have the most number of reviews, from the the most to the least.
              A registered user can also see this after login from her portal. The she can back to his own page by clicking the back button. (Done by: Jaydeb Sarker)

(Done by: Jaydeb Sarker)
"Top five cities": only root can see top five cities that have the most number of youtube videos. 

(Done by: Jaydeb Sarker)
"Popular tags": This is the most interesting one. root can see those tags which are used by every user who uploaded videos. 


(Done by: Asif Kamal Turzo)
"Common favorite youtubes": root can do and see the followings:                  
                            Given two users, X, and Y, which are specified by the user with two dropdown menu lists, 
                            list the youtube videos that are on both X and Y’s favorite youtube lists. 

(Done by: Asif Kamal Turzo)
"Productive users": root can see the users who have posted at least N youtube videos where N is a number specified by the root in a text field.
 
(Done by: Jaydeb Sarker)
"Positive reviewers": root can see those users that have given some reviews, and each review has a score of at least 3 stars.

(Done by: Jaydeb Sarker)
"Ambiguous reviewers" : root can see users that have given some reviews, for the same youtube video, the user gives one review with the highest score (five stars) and then another review with the lowest score (zero star).

(Done by: Asif Kamal Turzo)
"Collusion users": root can select a user pair (A, B). Then root will see did they are in a pair where they always gave each other "five star” review for every single youtube video they posted.

Moreover, it shows no result if any of above ten criteria does not exist in the system.
Lastly, root can be sign out by clicking sign out and moves to homepage.jsp.
