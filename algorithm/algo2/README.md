## Algorithm 2
algorithm - 125 points

Description
------------
The page at [host] has a list of subdirectories.  Each subdirectory has a page with a word on it.  Put the words together in order, take the md5 hash, and visit that page to retrieve the flag.
Oh, and the subdirectories regenerate every thirty seconds.

Hint
------------
[requests](http://requests.readthedocs.io/en/master/) may be helpful

Internal Description
------------
The website generates 7 random pages every 30 seconds and you have to take the text of each one and append it, then go to the md5 hash of the words put together and the flag will be revealed.

/eight
/funny
/yellow
/ducks
Flag Page - /cff436cf69d77a3bb9f374c04ed0ec23

Flag
------------
flag{c0ding_1s_c00l}
