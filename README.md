_(FORKED FROM: https://github.com/Pankaj1337x1998/AES-chat || https://web.archive.org/web/20210628124555/https://github.com/Pankaj1337x1998/AES-chat)_

**SINCE THIS REPO IS SIMPLY FORKED FROM THE ORIGINAL REPO JUST TO ARCHIVE IT. THE AUTHOR IS RESPONSIBLE FOR THE LEGAL STUFF WITH IT. (THIS IS JUST A SIMPLE CLONE.)** 

# AES-chat
This is a project intended to demonstrate the use of key exchange and encryption in a simple chat program. It establishes a shared encryption key with each connecting client through a Diffie-Hellman key exchange, which the client and server then use to encrypt and decrypt each-other's messages via AES.

Setup:

Prerequisites

1.Python 3
2.pycrypto
3.m2crypto

Client
$ python client.py [host] [--port]

Server
$ python server.py [--host] [--port]
