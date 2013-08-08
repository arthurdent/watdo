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

See also:

	$ ./watdo --help

wheredo?
--------

Put it in /usr/bin or add it to your $PATH in ~/.bashrc, or just run it from a directory, it'll work from anywhere.

whydo?
------

I'm a terminal monkey and all of the other cli twitter clients are kludgey and hard to navigate. This one aspires to suck less than the others.

todo
-----

* Display newsfeed.
