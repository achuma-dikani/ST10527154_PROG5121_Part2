# ST10527154_PROG5121_Part2
## Part 2 Repository
### What it is about
This adds messaging to the login system. After logging in, users can send multiple messages. Each message gets its own unique ID and hash. Messages can be saved in a JSON file or ignored.

### What It Does
Users must log in successfully before they can send messages. After login, users see options:
1.Send messages  
2.Show recent messages, which is not been added yet. 
3.Quit

#### Send Messages:  
You choose how many messages to send.  
For each message, you enter the recipient’s number and message text.  
The system checks the recipient number and message length.  
It generates a message ID and hash.  
You choose to send, ignore, or store the message.
#### Messages Storage:
Messages can be stored in a JSON file for later use.
#### Tests:  
The project includes unit tests to verify the message functions work correctly.

### How It Works
#### Message.java:
Handles message data, validation, hash creation, and saving to JSON.

#### Main.java:
Controls the program, login, menu, and message sending.

#### MessageTest.java:
Contains tests for message functions.

### How to Use It
Run the program and log in or register a new user.
After logging in, select option 1 to send messages.
Enter the number of messages you want to send.
For each message, enter the recipient’s number and the message text.
Choose if the user wants to send, store, or ignore each message.

