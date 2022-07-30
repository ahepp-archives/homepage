To run interactively:

    $ docker run --rm -it -v $(pwd):/ws -p 80:80 $HOMEPAGE_IMAGE
    > bundle install
    > bundle exec jekyll serve -s _src --livereload -H 0.0.0.0 -P 80
