WebBrowser
==========

C# Based Web Browser

Currently this project is just in the very early planning stages.

Currently with all of the "Mainstream" web browsers out today, none are written in C# or provide client side encryption or decryption functions using C#.

As of today if you need Client side encryption or decryption functions your only choice is using JavaScript and the code is in the open just view the source of the website and you get all of the encryption/ decryption details including the salts and etc.

One of the main goals of this project is to create a web browser that can use C# functions on the client side, which includes encryption/decryption methods.

Goals:

1. Client Side Encryption/ Decryption functionality to be able to push and receive data from a server in encrypted form.
2. Some how share keys with other Web browser users to beable to send back and forth encrypted data.
3. Encrypted Websites, A website can be created just for C# Web Browser users and for them the encrypted webpage will be      decrypted on the user side.  For regular browsers all they would see is a bunch of encypted data which makes no sense.
4. Massive Client Side storage of data to cache webpages, manage passwords,encrypted data and keys.  
5. API for web developers to use for the broswer to use the Client Side storage for their needs.  Like pushing their          website to the Client device and on next visit all resources are coming from client side and not the server.
6. Peer To Peer functionality using Web Sockets, ability to connect directly to another user without a central server.
7. Websites Shareable Cache Store, use for saving only things like one copy of each version of Bootstrap to use for all    websites that uses it, instead of saving a sperate copy of Bootstrap for every website even through they are all the   same. Other copies could be JQuery, and other commonly used images and frameworks.

9. Give Client side as much power and functionality that server side has.
10. A Web Broswer customized and made just for each person using it. 



