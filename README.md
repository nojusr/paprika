## paprika
This is paprika - a general purpose bot written in python 3.7, using the python library.

Features:
 - dynamic plugin support
 - multiple server support, with support for different nicks, plugins, command triggers for each server and even channel
 - decent selection of plugins, with lots more to come.

### Installation/Running
- clone this repository
- edit config.json to suit your needs (change nick, server, etc)
  - Make sure that you have added API keys for every plugin that needs one.
- remove any plugins (in /plugins) you don't feel like you need (every plugin has a description in the top)
  - NOTE: almost every plugin has a basic description and usage instructions in it's source file.
  - NOTE: do not remove admin.py, gadmin.py, ctcp.py
- install dependencies:
    $ pip install requests pydle beautifulsoup4 python-dateutil
- run bot.py in the root directory
    $ python bot.py

### Contributing
If you want to contribute, feel free to pick from any of the plugins listed below.
The code follows PEP-8 (although line length is a bit relaxed).