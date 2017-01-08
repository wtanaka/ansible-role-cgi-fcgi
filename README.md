[![Build Status](https://travis-ci.org/wtanaka/ansible-role-cgi-fcgi.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-cgi-fcgi)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-cgi-fcgi.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-cgi-fcgi)

wtanaka.cgi-fcgi
================

Installs cgi-fcgi, a bridge from CGI to FastCGI

This command can be used for debugging a fcgi setup (e.g. php-fpm by
making it easier to send synthetic test requests directly to the fcgi
server)

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: wtanaka.cgi-fcgi

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
