# encrypted-chat-project

hello hello hello!

im creating a decenteralised chatting program, for now its very early in the development.
please contact me if you want to contribute to this project at swizex@gmail.com

the program will be completly encrypted end to end,including most of the database.

i am planning on isolating all the parts of the backend program in order to minimise the risk of
it being breached.

user data will be stored in an encrypted server that will only be connected to the main server that
will be running the backend program.

public key data will be stored on a third server that is also encrypted and only accessible via the main
server.

so,so far we have 3 servers that cross talk between each other when needed, lowering the chances of
getting the data stolen from a breach into one of them,ofcourse that if the main server is breached
all data and traffic is encrypted, so as long as the private key of the server is not avaliable to the
intruder,we will be fine.

the main idea of this program is that the server encryption and client encryption will be different,
this way we make sure the server doesnt know what the clients are sending or receiving,making it more secure.

the public key of clients chat room will be sent via invitation to people from his friends list,this way it
wont be accidently leaked if the main server is breached,since client side encryption keys are all local
to the client themselves.

i am creating a simple recovery system that uses QR codes as a recovery signature that only it can reset the 
password the client set up to his account, key itself is also encrypted using the servers encryption key.

i am also going to implement the QR code system into the invitation of other people into your friends list,
this way its easier and faster to add people to your account without much hassle.

the chat rooms themselves are going to be peer to peer based,this way the server isnt the weak link in this possible
security risk,all data between the room is encrypted using the owners private chat key.

i am also considering implementing a VPN to isolate the chat rooms from everything else.

the client software will be avaliable on windows/linux aswell as android,making it easily avaliable
to everyone.

developed by teddy morduhovich.
