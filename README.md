# Maldives Open Source Society's website

[MOSS Website](https://github.com/mossmv/mossmv.github.io), the current host of
[mossmv.github.io](http://mossmv.github.io) is on Github Pages we desire to find
a new long term solution to host the website. The current thought is to using a static site generator,
[Jekyll](https://jekyllrb.com/). This repository is attempt at that. It is now live at
[mossmv.github.io](mossmv.github.io).

## Developing

* Install the version of Ruby specified in [.ruby-version](.ruby-version)
  * Usage of [rbenv](https://github.com/rbenv/rbenv) recommended
  * `gem install bundle`
* Install [`yarn`](https://yarnpkg.com/en/docs/install) (used for managing external asset libraries (like Bootstrap,
  jQuery, etc.)
* Run `make`

If you add a new external resource, be sure to add lines to the relevant [`Makefile`](Makefile) target to copy
them into `css/vendor` and `js/vendor`.

## Making Changes

The _config.yml file has the site wide changes

Other data are included in _data folder

You can make changes to the template files or the data

### Template files

The layout files are included in _layout folder and _includes folder

In order to make changes to the template files, just edit those, these includes, index.html, sponsor.html, events.html, donate.html, blog.html, about.html /join/index.html, about/*

### Data Entry

Day to day data need to be entered to _events, _posts, and _projects
