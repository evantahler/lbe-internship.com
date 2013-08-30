# The ETC Creative Good Fund.
### http://www.lbe-internship.com/
### https://github.com/evantahler/lbe-internship.com

## How do I build the site?

this is a static site hosted by [Dreamhost](http://dreamhost.com/).  We use [Jekyll](http://jekyllrb.com/) to build the site and test it locally.  Here's a quick guide:

- install [Ruby](http://www.ruby-lang.org/) (comes with OSX)
- [git](http://git-scm.com/) clone this project
- [install](http://gembundler.com/) bundler
- install the gems this project needs with `bundle install`
- run jekyll `jekyll server --watch` which will run this site locally on port 4000.
- You can build and deploy the site simply with `./deploy` (assuming Evan granted you access to the server)