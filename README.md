# Frozen Flask + Github Pages (updated)

An example of how you can make static sites with [Flask][] and deploy them for free on [Github Pages][].

See [ORIGINAL] the blog post [here][article].

This is my take on this project for github pages to host a static site.
I plan to migrate my [website][my_site] from google app engine to github pages.

I figured I hedged my bets when it comes to hosting service I use to serve my tiny html only website.

Below is instructions on how install local virtual env to run flask web server with run.py and freeze.py to build static content which can be pushed to git and immediately get reflected on git hub pages,

```bash
$ pip install -r requirements.txt
# Run local server
$ python run.py
# Build static content
$ python freeze.py
```

## you can find the live site [here][live_site]

## License
Licensed under the [WTFPL][].

[live_site]: https://gokulmenon.github.io/gokulmenon/
[article]: http://www.stevenloria.com/hosting-static-flask-sites-for-free-on-github-pages/
[example]: http://stevenloria.com/flask-ghpages-example
[Flask]: http://flask.pocoo.org/
[WTFPL]: http://www.wtfpl.net/
[Github Pages]: http://pages.github.com/
[my_site]: https://www.gokulmenon.com