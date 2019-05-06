# Comp Eng project log

## May 1:
Pi was set up. Packages were updated and ssh was set up for remote connections so that both of us can work on it at the same time. Key pairs were generated so that future connections remain secure but passphrase is not neseccary so time saved. Initial python testing code was run via the socket library for TCP and was successful.

## May 2:
Looks like the parameter for connection.recv() describes how many characters received at once instead of bits/bytes received. Investigation: why does the code send a small message for every chunck? 

## May 6:
Used ssh-keygen to allow us ssh access to the pi without using the password. This will only work for our machines. Experimented with sending messages via TCP to and from the pi.

## May 7:
Created a primitive blackjack game in python using the client-server model. The pi runs a TCP server and acts as the dealer, any client can connect and play a game of blackjack. 