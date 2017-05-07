Overview
--------

Basic demo of Robot framework. There is a screencast that
walks you through the process of making it happen (Russian):
https://youtu.be/TOaKn88jFIo 


Prerequisites
-------------

- Robot framework
- Selenium2Library
- Browser webdriver

Installation instructions are available at: https://github.com/robotframework/robotframework/blob/master/INSTALL.rst


Example test
------------

This is what the tutorial does:

#. Open browser
#. Go to address ``http://google.com``
#. Type name of a country (choosing it from a set of test data)
#. Click ``Search``
#. Wait for the results to load
#. Ensure that the capital of that country is displayed somewhere on the page
#. Repeat these steps for all the given test data
#. Close browser
