SimpleCounter
=============

Simple redis based nginx counter


First of all you need to install http://wiki.nginx.org/HttpRedis2Module
Then activate SSI module if not active

to activate counter place
<!--#include virtual="/redis-<page-name>"-->
at the bot of your page template
where <page-name> is name of redis set key
