supybot-Trac-plugin
===================

Extremely simple plugin to interact with a Trac instance and view tickets
from an IRC channel.

Requisites
==========

 * Python 2.5+ (recommended 2.7)
 * BeautifulSoup 4

Installation
============

 * Copy the Trac directory to your plugins directory inside your supybot
   config. Be sure that the plugins directory is in the supybot conf
 * Edit the Trac/config.py file and edit the TRAC_URL to your like, pointing
   to your trac installation.
 * Tell the bot to load it with "load Trac"

Usage
=====

This plugin has at this time just one command:

 * **view** <ticket number> - Returns the ticket number with the summary.
