# Auction Manager in Java

Distributed application that allows the management of auctions. There are two identities: selles and buyers.

At each moment the seller can close the auction and the highest bid wons.

It was developed a client and a multi-threaded server. The communication between these client and the server is made by TCP sockets.

The client server communication protocol is line-based.

Some functionalities are:
* Register an user
* Start an auction (with an item description)
* List all active auctions
* Bid on an item
* Close an action


This project was developed in the context of Distributed Systems program @ uminho