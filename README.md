## Skyport Systems Landing Page

Site built with [Jekyll](http://jekyllrb.com/) static webpage generator.

[Github pages](https://help.github.com/articles/using-jekyll-with-pages) automatically compile jekyll projects. Any changes committed to this repository will be live almost instantaneously.

## Running site locally

* [install jekyll](http://jekyllrb.com/docs/installation/)
* $ cd repository directory
* $ jekyll serve --watch
* navigate browser to http://localhost:4000/


## Build site locally

* $ cd repository directory
* $ jekyll build --destination <destination>


## MB removed this: Precompile assets

The less stylesheets need to be compiled before pushing to github.

* install [less] http://less.github.io/#installation
* cd repo directory
* $ lessc -x assets/styles/skyport_systems.less > assets/styles/skyport_systems.min.css


## TODO

* [x] precompile less.
* [X] change robots.txt to allow indexing if/when golive.
* [ ] create faveicon.ico

