# lastblogzz

This python web-app was created to emulate a blog and the different user types available.Developed during Moringa Core. This is Week 6's Independent Project.

## Description
This web-app allows the user to view,comment and like blog posts.The admin can add/delete posts and delete comments.

## Setup/Installation Requirements
*Click on the green button written clone and copy the URL

*On your terminal 

 -run `git clone https://github.com/EmmanuelWanzala/pblog.git`

 -cd pblog

 - Run the command `code .` or `atom .` depending on your text editor

### Known Bugs
One can like as many times as possible,not once for each user as was intended

## Live link to the project

https://lastblogzz.herokuapp.com/

### Behaviour Driven Development
* The program should return all posts on the home page<br>
Given:All posts<br>
When: View is changed to home page<br>
Then: All Posts are displayed<br>

* One should receive an email when signing up,subscribing and when a post is made<br>
Given:A sign up/subscription/post feature<br>
When: Email is validated <br>
Then: Email is sent to the email registered with<br>

* The program should abstract data<br>
Given: A user's role is "User"<br>
When: User logs in<br>
Then: Admin features are not shown<br>

* Likes/Comments should be recorded and displayed to all the users<br>
Given:A like/comment option is given<br>
When: User likes/comments a pitch <br>
Then: The value is added to the number of likes/comments<br>


### Technologies Used
* Atom was the source code editor of choice.
* Git and Github were used as my local and online repositories respectively.
* Flask was used as the micro-framework
* Heroku was used in deploying the live site
* Gmail was used as the email sender


### Support and contact details
* Contact me through my email: donald.k.kiplagat@gmail.com
* The source code is also contained within the folder containing this ReadMe with comments on the code thus third-party support can be offered.

### License
MIT LICENSE :https://spdx.org/licenses/MIT.html