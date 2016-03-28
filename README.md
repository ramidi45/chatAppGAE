chatappUsingGAE
===============

URL: http://1-dot-chatappgae.appspot.com/myapp


Multi chat application with document sharing (for viewing purpose)
===========================================================================
built using Java Google app engine sdk on Google App engine
any number of users can login and chat with each other
user roles: admin and normal user
admin user: admin user can select a file from his google drive and share file with other users in chat.
only admin can start document sharing.(to test this use below login details)
test login id: gaetarun@gmail.com (has admin role)
test login pwd: gaetarun123

Future scope:
===============

1. To make use of html canvas & websockets: for simulating blackboard experience by broadcasting changes from admin user.
2. To make use of html5 webrtc: for video sharing where admin video feed is shown to users.

Services used: 
===============
1. Google user authentication 
2. Google channel api : for sending messages 
3. memcache : to store chat history; will be used for showing history to users who logged in later
4. Google drive picker api : to select and load files from google drive
5. Google docs viewer api : to view any format docs

