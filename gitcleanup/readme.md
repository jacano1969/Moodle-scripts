Git cleanup
=============

Helps you cleanup your github account, so that you can get rid of unused branches

Version list
--------------
* 0.5 3/04/12 First version push
* 1.0 (beta) 

Installation
-----------------
* Copy all files to any folder in your www director
* Edit config.php as per your needs
* Access index.php from browser
* Most of the time the script worked fine, but occasinaly it would go nuts and send distress singal to aliens. So use at your own risk!!


Requirments
-----------------
* Uses Curl
* Uses simpleXml

To Do
-----------------
* Add support of oauth
* Convert the script to use V3 of the github api
* Pagination?
* Debugging
* Display the authentication exception properly.

Please Note:-
----------------
A lot of updates has been made to the php api lib (http://develop.github.com/p/repos.html) to support various things inlcuding but not
limited to "Delete requests", V3 of the API etc. so if you decide to update the lib to a latest version, make sure you are copying those
changes as well:)

Credits
-----------------
* It must be the energy of Spartans that drove me to write this crapy script :D, so lets just thank their god Zeus :)