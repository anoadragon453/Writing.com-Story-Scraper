A Writing.com Story Scraper
==================

With the recent unexplained story take-downs on Writing.com, I wrote a little script to download/archive an entire interactive story and package it into a folder that you can browse with your browser.

All it requires is a login and story URL.

Installation
============

This script depends on a few different libraries to function properly. 

First and formost, make sure you have [Python](http://python.org/downloads/) installed.

Then, install the following dependencies either through `pip` or manually:

* `mechanize`
* `html2text`
* `yattag`

Once installed, `cd` into where you've downloaded the script and run `python writing-scraper.py`.

### To do:

* Create a file for the initial "Entry Point" for an interactive
* Download stories other than interactive (though who really even reads the other ones?)
* Debug mode
* Zip/Rar contents after retrieval
* Make generated HTML more beautiful
