## Overview ##

The goal of this project is to provide a thin layer around the Salesforce SOAP messaging that consumes both the Enterprise and Partner WSDL formats and implements the Salesforce API 17.0 spec.


The Salesforce Python Toolkit features the following:
  * Support for both the Enterprise and Partner WSDL
  * A single, unified interface to Enterprise and Partner methods and objects
  * Transparent SOAP interaction management
    * Endpoint rewriting
    * SOAP header management
    * SOAP namespace prefix handling for methods and objects

Included in the tarball is [EXAMPLES](http://code.google.com/p/salesforce-python-toolkit/source/browse/trunk/EXAMPLES), which includes a code example for every Salesforce API method call.

## Installation and Dependencies ##

The Toolkit can be installed by typing `python setup.py install`.  It requires Suds 0.3.9, which will be automatically installed.

## Source ##

The source is currently available via anonymous SVN and as a tarball.  Release snapshots can be found in tags/.<br />
If Git is more your style, Rich Atkinson has mirrored the source [on GitHub](http://github.com/atkinson/salesforce-python-toolkit).

## Feedback ##

Please feel free to drop me a line at dlanstein gmail com if you have any feedback, it would certainly be appreciated.

## Acknowledgements ##

I would like to thank my employer, [Splunk, Inc.](http://www.splunk.com), for donating time to this and many other open-source projects (like <a href='http://code.google.com/p/eloqua-php-sdk/'>this one</a>).

I would also like to thank <a href='http://joshuakugler.com/'>Joshua Kugler</a> for his contributions past and future.  His efforts are reflected in the 0.1.4 release of the Toolkit.

Lastly, I would particularly like to thank my colleague [Gareth Watts](http://omnipotent.net), without whose invaluable advice and guidance this project would not exist.