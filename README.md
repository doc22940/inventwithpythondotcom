inventwithpythondotcom
======================

The InventWithPython.com website source

The [InventWithPython.com website](http://inventwithpython.com) is generated using [Jinja2 templates](http://jinja.pocoo.org/).

## How the files are organized in this repo:

* `content` - HTML pages used with the templates
* `templates` - Jinja2 templates
* `static` - HTML, images, and other static files
* `output` - The complete website is put here after running `generateSite.py`
* `generateSite.py` - A Python 3 script that produces the files to put on the site
* `runServer.py` - A Python 3 script to run a web server on localhost:8000 to preview the site locally
