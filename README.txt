What is this?
=============

An event based Plone product.
Add some configuration to your Plone site for sending email on new messages or replies
added on forums.

You also need `Ploneboard`__ product to be installed.

__ http://pypi.python.org/pypi/Products.Ploneboard

Tested on
---------

* Plone 3.3 (Ploneboard 2.1)

Plone 2.5: still live
---------------------

Yes, this is done to be compatible with Plone 2.5 and older versions of Ploneboard.
To install this for Plone 2.5 just copy the *PloneboardNotify* directory in the *Products* directory
provided by older Zope releases.

**Please note** that you need *Five 1.4* to run the tests on Plone 2.5.

Thanks to
---------

* **Nicolas Laurance** for giving french translation and for helping adding other features.

TODO
----

* Current version support global configuration and forum specific ones; the long-term
  plan wanna reach also forum area configurations.
* Also manipulate the FROM part of the mail, configurable globally, for single forum, etc.
* Forum outside the Forum Area are not supported by the configuration UI.
* A complete, clean uninstall procedure that remove all unwanted stuff.

