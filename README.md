Facebook Birthday Response
=========================
Python script that automatically thanks all users and like their birthday wishes on your timeline


Author
------
Arpan G <arpan.neo@gmail.com>


How to use
------------
Configure parameters and run the script:
- bday: your birthday as in the following datetime(year, month, day[, hour[, minute[, second[, microsecond[, tzinfo]]]]])
- access_token: Generate one at https://developers.facebook.com/tools/explorer make sure you have all the required access when you generate the token
- like: set true to like posts on your wall
- comment: set true to comment thank you
- message_set: the list of messages from which you want a random message to be selected
- use_filter: if false, repies to every message. Make it false if you are sure every wish posted on your wall is a birthday message
- bdaywords: keywords to respond to. Comment only on posts containing at lease one of these words


License
-------
This project is licensed under the terms of the MIT license. See LICENCE.txt for details


Discalimer
----------
This code is modified form of what was at https://github.com/rishirdua/facebook-birthday-response.

Credits
-------

Idea inspired from a post on quora: http://www.quora.com/What-are-the-best-Python-scripts-youve-ever-written
Coincedently the same post inspired me!! Instead of writing I searched for the code first ;)
The code in that post uses FQL which is deprecated after v2.1. This implementation uses Facebook Graph API.
