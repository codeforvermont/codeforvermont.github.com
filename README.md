Code for Vermont Website
========================

This is the source code for the [codeforvermont.org](http://codeforvermont.org/) website.

Developing
----------

This website is built using [Jekyll](http://jekyllrb.com/), a blog-aware static 
site generator. In order to run your own local web server, see the instructions 
on [installing Jekyll](https://github.com/mojombo/jekyll/wiki/install). Once installed,
Jekyll can be run locally by running the following command from the root of this 
project:

    $ jekyll serve --watch

The website should now be available on `localhost` port `4000`:  
`http://localhost:4000/`

See the [usage instructions](https://github.com/mojombo/jekyll/wiki/Usage) for more 
information on working with Jekyll.

Deploying
---------

This website is configured to be deployed using the [GitHub Pages](http://pages.github.com/) 
feature of GitHub. Deploying is simply a matter of pushing the `master` branch to 
GitHub.
