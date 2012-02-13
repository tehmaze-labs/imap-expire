=============
 imap-expire
=============

Expire messages in IMAP(s) folders.


Requirements
============

* Python
* [Python keyring](http://pypi.python.org/pypi/keyring)
* Some keyring implementation (Gnome Keyring, OSX KeyChain, etc.)


Usage
=====

Look at expire.cfg.sample for an example. Accounts are defined in a "account"
section, the folders for that account in an "expires" section. The format
of the latter is "mailboxname = days".


Bugs
====

Use the [GitHub issue tracker](https://github.com/tehmaze/imap-expire/issues).
