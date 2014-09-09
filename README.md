# Source for the course website

Source for generating and uploading a [template website Stat
133](http://berkeley-stat133.github.io/]) at the url:
[http://berkeley-stat133.github.io/](http://berkeley-stat133.github.io/]). This
uses

* [pelican blog generator](http://blog.getpelican.com/)
* [pelican-boostrap3 theme](https://github.com/DandyDev/pelican-bootstrap3)
* [pelican plugins](https://github.com/getpelican/pelican-plugins)


## Installation

You will need to use `pip` to install some Python packages.

    pip install -r requirements.txt

## Developing

To run Pelican in regeneration mode and serve the output at
http://localhost:8000, type:

    make devserver

Once you are happy with your changes, type::

    make stopserver

## Publishing

To build the site and push it to github, type:

    make github

The updated page can be viewed here: http://berkeley-stat133.github.io/

