Candor CMS Demo
===============

A demonstration of [Candor CMS](http://github.com/fhd/candor-cms).

Concepts
--------

A Candor CMS website consists of pages, templates and articles. The
system is completely file-based, so each of these are simple files
placed in respectively named directories.

### Pages

All files in the *pages* directory represent distinct pages of the
website, each mapping to a different URL. These files can either be
requested by their full name (e.g. http://example.org/index.html) or
by their basename (e.g. http://example.org/index).

### Templates

*Not yet implemented.*

Templates will provide a way to reuse code among pages.

### Articles

*Not yet implemented.*

While pages and templates fulfil technical purposes, articles will
hold the actual content of the website. Pages and templates will be
able to list and display articles.

Running the Demo
----------------

First you'll have to get both this demo and Candor CMS, best via Git:

	git clone git://github.com/fhd/candor-cms.git
	git clone git://github.com/fhd/candor-cms-demo.git
	
Then configure the absolute path to candor-cms-demo in the file
*src/main/resources/candorcms.properties* in the candor-cms directory.

Now refer to the candor-cms README file for instructions on how to run
it in a local server and open the URL in a browser. You should see the
demo website.
