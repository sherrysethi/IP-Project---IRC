IP-Project---IRC
================
This flavor of the Internet Relay Chat is coded using pyton version 2.7. The application is Unix compatible.
I have used oops to maintain the state of variables. I have used ”select.select()" to manage multiple connections from clients.

To start the IRC Session:

1. Execute server.py
	python server.py

2. In new terminal execute client.py
	python client.py



List of commands

1.register
Use:/register username pwd
This command is use for user registration.
example :
	/register user password


2.exit 
Use :/exit
Command to exit IRC.
example:
	/exit

3.msg
Use :/msg to message
Command to send private message to a user.
example:
	/msg user hello		


4.create
Use: /create roomname
Command to create a room.
example :
	/create CSRoom 	

5.join
Use : /join roomname
Command to join a room.
example:
	/join CSRoom
	 
6.mroom
Use :/mroom roomname message
Command to post in a room. You can only message to a room if you are a member of a room
example:
	/mroom CSRoom Hello all, welcome.
		 
7.listrooms
Use :/listrooms
Command to lists all the rooms in the IRC session.
example:
	/listrooms

8.list
Use :/list room
Command to list all the users in the room


9.login
Use :/login username password 
Command to login in to IRC.
example:
	/login user pwd
	
10.clsscn
Use :/clsscn
Command is to clear the client screen.
		
		
11.nick
Use :/nick new_username
Command to change your own username.
example:
	/nick newuser.

12.pwd
Use :/pwd new_pwd
Command to change your own password.
example:
	/pwd newpwd

13.leave
Use :/leave room
This command is to leave a room.
example:
	/leave CSRoom

14.invite
Use :/invite room user-list
Command to invite users in a room.
example:
	

