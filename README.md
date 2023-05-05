# hello-world

There are versios ways you can create a preview of any github sha, tag or branch
the syntax is as follow:
```
https://*.localwebcontainer.com/{optional_deeplink}?installFrom=gh/{:owner}/{:branch}@{sha|branch|tag}
```

Here are some few examples:

### Install from github repository:
- https://hello-world.localwebcontainer.com/?installFrom=gh/Local-Web-Container/hello-world@main


### Install from github repository deeplink:
- https://hello-world.localwebcontainer.com/README.md?installFrom=gh/Local-Web-Container/hello-world@main


### Install from specific github commit:
both long and short sha works fine
- https://hello-world.localwebcontainer.com/README.md?installFrom=gh/Local-Web-Container/hello-world@56fe3e7
- https://hello-world.localwebcontainer.com/README.md?installFrom=gh/Local-Web-Container/hello-world@61e5e3229ebf3990f058d28273f3f4294daf455c


### Installing from referer
With a static link like: https://localwebcontainer.com/?installFrom=referrer then, we will figure out where you came from and take that specific repo / commit / pr / branch and use that
