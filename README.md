watdo
=====

This thing still needs a lot of work. It doesn't read your news feed yet, but it allows you to tweet from the console. It's a complete WIP. Consider it pre-alpha.

Dependencies: curl, perl, cut, openssl, base64

watdo?
------

1. Tweet

howdo?
------

	$ ./watdo "Hey, I'm tweeting!"
	$ ./watdo <<< "Hey, I'm tweeting!"
	$ echo "Hey, I'm tweeting!" | ./watdo

wheredo?
--------

Put it in /usr/bin or add it to your $PATH in ~/.bashrc, or just run it from a directory, it'll work either way, because everything is contained in one file.

whydo?
------
I'm a terminal monkey. There is really no simple command-line app for twitter. There are a few that are kludgey and hard to navigate. This one sucks less than those ones.

todo
-----

1. newsfeed
2. remove cut as dep
3. remove perl as dep?
4. feature requests.
