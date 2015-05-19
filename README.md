watdo
=====

Dependencies: bash, curl, coreutils/busybox, openssl

watdo?
------

1. Tweet from the console.

howdo?
------

	$ ./watdo "Hey, I'm tweeting!"
	$ ./watdo <<< "Hey, I'm tweeting!"
	$ echo "Hey, I'm tweeting!" | ./watdo

See also:

	$ ./watdo --help

wheredo?
--------

Anywhere:

Run as `./watdo`, copy `watdo` to /usr/bin, or add it to `$PATH`.

whydo?
------

I hate dependencies more than I hate bash. Also writing a real JSON parser in bash is funny.

todo:
-----

* Display newsfeeds.
	* Finish JSON parser
