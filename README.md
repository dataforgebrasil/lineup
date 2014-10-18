lineup
======

## PHP-Ajax Line Counting System

##What is Lineup
The Lineup system is used to replace or used with a turn-o-matic, a take a number queue system used at banks and stores to set your place in line.   You look up at a counter seen in the store to see when your number is called.  Lineup is being developed to advance this system to todays new computer world with new advanced features.  

##Lineup basic standard features
* As you would expect it has the same basic features as turn-o-matic with a monitor with a big 2 digit number displayed indicating the number of the customer presently being served.  Example:  Ready to server customer: 05.

* Optional feature can be enabled to include  the present number of the counter  that is being served to that number.  Example:  ready to serve customer  06 at counter number 2.

* Added automated human synthesized voiced sound or just a beep to announce changes in the queue to get the attention of customers without watching the display and to benefit those that have disabilities with limited sight.

* User account can manually override counter to reset to a new start queue number point (start of day reset).



## What is needed for a Lineup system
* A standard turn-o-matic ticket dispenser or small thermal strip printer

* A small Linux system that runs the lineup system software package.  A minimal $35 Raspberry Pi Linux system or equivalent would be all that's needed to run the system from.  

* A computer monitor small or large to display the queue status to the customers and optional ETA estimated time status.

* User client systems that can be any standard computer system, tablet, android phone or other device that has a browser that counter personel will use to update the Lineup system counter status.

* Optionally a wifi device or wifi access point to hook to the Lineup system for customers to connect to , to view there queue status remotely in the store.

* Optionally an Internet wan ADSL or other Internet connection for the Lineup system to allow updating queue status to be seen remotely on the Internet.

* Optional wireless wifi or bluetooth device or hardwired switch to Lineup system to update counter status.

## What runs inside of the Lineup system
A lineup system is a set of easily installed software that runs on a Linux ubuntu or mint server system with a deb package or can be ported to run on most any Linux system.  Lineup basically installs as a website that runs on a local or even a remote Linux system under an apache2 server with added mysql support.  The other client parts and counter display of Lineup are just standard computer systems that run any standard Internet browser for example Firefox, IE or most any other browser from a computer, tablet or standard android phone or other. 

## Future options we hope to be added later to Lineup

* Multilevel admin, users and guest login levels.  Admin can add, delete or change users that have the privilege to update the counter that they are assigned.  User level accounts can login to there counter number to allow update of the counter for there workspace.  At default guest level a guest can see the present queue numbers being served if guest level is enabled.

* HTTPS encryption (self signed or class 2) can be added to secure the Lineup system if used with the wifi or wan option to prevent the system from being hacked by remote or local guest users.

* Add to the queue screen a small rate indicator of the average time it has been taking to serve the last X customers  so that people can estimate for themselves about how long they will have to wait.  

* A customer can use a browser in an advanced android or other phone to connect to the local wifi of the store or a wan connection if they have one, and check the status of their queue number in the store from a remote location or from within other parts of the store.

* On the browser of a phone or on a local terminal one could check the ETA (estimated time before service)  before a customer will be served.

* With the added optional ticket printer, added to the printed ticket a QR code bar code of the URL can be  added to the ticket that contains the URL and params to point to the website of the  persons status in the queue of the store and his ETA estimated time to be serviced.  This QR code can be scanned and processed from standard software already available on smart phones with the QR code software installed.  This feature can also be used manually without the QR code.

* With the optional wifi feature added, people that connect to the stores local wifi access point with phones or other devices, can be auto redirected to the Lineup website for this store to display the queue status and eta stats.
