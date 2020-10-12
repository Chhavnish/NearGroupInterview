# NearGroupInterview
A social media photo sharing website built on Django Framework.

The features available to users :-
1) Post images.  A short description and tags can be included if desired by user.
2) can check everyone's post and also like and comment on the photos.
3) Users can edit or delete their photos too.
4) Users can search for posts by tags and for other users by their username.
5) Without authentication, users can view the posts but cannot like or comment.
6) Registeration system is complete with password reset option also available to users.
7) Users can edit their profile including profile pic and a short bio about them.
8) Users can view profile of others users and can send them friend requests.
9) Users can send friend request, cancel requests, accept requests, reject requests or even unfriend their friends.
10) Users are given suggestions for new friends based on mutual friendships.

Technologies used :-
1) Frontend: HTML5, CSS (Bootstrap4 + Custom CSS), AJAX
2) Backend: Django

To run the Application
1) Install Python 3
2) Install pip
3) Go inside Project directory and run command *pip install -r requirements.txt*
4) Setup below environment variables in bash file of your 
  - EMAIL_HOST_USER # export EMAIL_HOST_USER="<Your Email id>"
  - EMAIL_HOST_PASSWORD # export EMAIL_HOST_PASSWORD="<Your Email password>"
5) run command python manage.py runserver
6) Open your Browser and Try it out at: http://127.0.0.1:8000


This repository is open for contribution. If you have any improvement in mind, you should make the pull request with relevant details and I shall add it.
