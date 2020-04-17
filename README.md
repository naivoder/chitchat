# chitchat
Messenger application that automatically translates to/from language of user

**Background**

This application is intended to work as an instant messenger.
The idea is to translate all incoming messages into a language of your choice.
Two people speaking different languages would be able to chat, each seeing the conversation in their native language.

**Requirements**

This project makes use of four modules:

1) socket 
2) threading
3) tkinter
4) googletrans

Socket, threading, and tkinter are included in most python distributions. 

Googletrans can be installed via ```pip install googletrans```

**Command Line Instructions**

To demo the project:

1. In terminal window, navigate to directory and enter command ```python3 server.py```

2. In new terminal window, enter command ```python3 client.py```

  1. Enter local host address (127.0.0.1)
  
  2. Press ```enter``` to accept default port 
  
  3. Follow instructions in GUI window, enter language as english
  
3. In new terminal window, enter command ```python3 client.py```

  1. Enter local host address (127.0.0.1)
  
  2. Press ```enter``` to accept default port
  
  3. Follow instructions in GUI window, enter language as spanish
  
4. Chitchat!

**State of the Project**

Help wanted! All collaborators are welcome. Currently, the project only works as a demo between English and Spanish.

Features Needed:

1) Support for all languages
2) Improved UI
3) Mobile application
