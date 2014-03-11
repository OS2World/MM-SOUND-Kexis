Kexis - An opensource lossless WAV file compressor.
Copyright (C) 2000 Wayde Milas (wmilas@rarcoa.com)

Kexis comes with ABSOLUTELY NO WARRANTY; for details see included GPL license
This is free software, and you are welcome to redistribute it under certain
conditions; for details see included GPL license

This software is still in the development stage. It IS functional. It will happily compress and decompress and yield (I hope) correct data. However, being still in development, Kexis is NOT optimal in speed, or size compressed. Its an ongoing project.

NOTE: Until we hit 1.0.0 I will try my best to keep backwards compatability in file formats. HOWEVER, I CANNOT guarantee it. Since Kexis compresses and decompresses much faster than realtime (On modern intel hardware) if it comes to converting back to wav and then encoding with a new version should not be a problem.

Install:
-------
type make
pray
move the resultant executable kexis whereever you want it to go.

Credits:
-------
I'd like to thank a few people who have helped with the coding of hexis.
* Gerard Saraber (gsaraber@rarcoa.com): Helped immensely in debugging some of the nastier bit issues and constructing some bit transforms. This project is probably just as much his as it is mine.
* Matt Ashland (email@monkeysaudio.com): The initial Kexis was based off the techinal documentation on the Monkey's Audio site (www.monkeysaudio.com). Matt helped immensely explaining how Monkey's Audio works, and tossing some great suggestions my way when I got stuck.

For Features, FAQ, Bugs, Changelog, and Todo list please see:
http://sourceforge.net/projects/kexis/
