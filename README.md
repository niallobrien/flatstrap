Flatstrap
=========

This is a work-in-progress Flat UI "inspiried" theme for Bootstrap, but in 100% less (as it should be).

Clone Flatstrap, change into the directory and clone Bootstrap.

	git clone git@github.com:niallobrien/flatstrap.git
	cd flatstrap
	git clone git://github.com/twitter/bootstrap.git

It currently looks like this:
![Flatstrap](http://dl.dropbox.com/u/14373373/Screenshots/1v.png?raw=true)

When compiling the less files yourself, simply compile /flatstrap.less and it should import all it needs.

Contributing
------------
I'd really appreciate all the help I can get.

To override or customise a part of Bootstrap, find the corresponding less file in /bootstrap/less/ and copy it to /flatstrap/less/. Then you must import it in /flatstrap.less in the same order that Bootstrap imports it (see /bootstrap/less/bootstrap.less) 

Once done, simply edit the file you just copied, and only keep the bits that you are customising, remove the rest.

Enjoy! :)

Niall.
