# My Academic Website

My academic webpage is automatically generated using [Jekyll](https://jekyllrb.com) and hosted on [Github](https://github.com/ilariobonacina). 


The source code for it is in `~/Sylonogy Drive/_my_website/my-website-source`

## How to test the changes

To edit the changes use Atom. To test run the changes

`bundle exec jekyll build --incremental --watch`

`bundle exec jekyll serve`

To see the changes go to `http://localhost:4000`

or just look at the link given in the terminal output.

## How to push the changes online

Copy the content of _site in the github folder, commit and push-it GitHub and wait! 

*GitHub might be super slow in pushing the updates to the website!*

## Plugins

**Jekyll-scholar** is a plugin to automatically generate bibliographies from .bibtex files.
jekyll-katex (documentation) a plugin to write math in Jekyll posts and KateX.

## Tips ad Tricks

To force a line return, place two empty spaces at the end of a line.

### Errors

There are always errors due to ruby probably. Maybe XCode is not installed.

