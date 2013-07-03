Quirkies: PEAR-Channel
======================

This repository contains the source files of the Quirkies PEAR channel
at [http://pear.quirkies.org/]. It is a resource for various packages,
with focus on Composer (back-) ports.


Synopsis
--------

Registering the channel:

	pear channel-discover pear.quirkies.org

Listing available packages:

	pear remote-list -c quirkies

Installing a package:

	pear install quirkies/package_name

Installing a specific version/stability:

	pear install quirkies/package_name-1.4.0
	pear install quirkies/package_name-alpha


Other Resources
---------------

Receiving updates via feed:

	http://pear.quirkies.org/feed.xml

Browsing the source-code:

	http://github.com/quirkies/


Notes
-----

The Quirkies PEAR Channel is powered by Pirum (http://pirum.sensiolabs.org/)
and GitHub Organization & Project Pages, with custom DNS resolution. See
http://help.github.com/articles/setting-up-a-custom-domain-with-pages for
more information.


