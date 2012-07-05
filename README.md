serviceup
=========

A simple service monitoring daemon written in Python

1. Configuration is super easy. Follow the examples in config.ini to setup your own services.
2. Start the daemon with ./serviceup.py start

As of now there is only support for http and https. However, this daemon is expandable and
future plans include support for ping, mysql, apache solr, and APNS (Apple's Push Notification Service)

By default the daemon will check each service every 5 minutes. The frequency can easily be changed in
serviceup.py. There are several advanced cofiguration variables in serviceup.py which can be configured
to your liking. For example: the from email address, log directory, etc.
