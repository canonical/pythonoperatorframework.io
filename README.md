![pythonoperatorframework.io](https://user-images.githubusercontent.com/6353928/94026467-9dff1480-fdb1-11ea-8026-e866246815fc.png "The Python Operator Framework")
# pythonoperatorframework.io

![Github Actions Status](https://github.com/canonical-web-and-design/pythonoperatorframework.io/workflows/master%20checks/badge.svg) [![Code coverage](https://codecov.io/gh/canonical-web-and-design/pythonoperatorframework.io/branch/master/graph/badge.svg)](https://codecov.io/gh/canonical-web-and-design/pythonoperatorframework.io)

The Python Operator Framework provides a simple, lightweight, and powerful way of writing Juju charms, the best way to encapsulate operational experience in code.

This repo is the application for the [pythonoperatorframework.io](https://pythonoperatorframework.io/) website.

The site is largely maintained by the [Web and Design team](https://ubuntu.com/blog/topics/design) at [Canonical](https://www.canonical.com). It is a stateless website project based on [Flask](https://flask.palletsprojects.com/en/1.1.x/) and hosted on a [Charmed Kubernetes](https://ubuntu.com/kubernetes) cluster.


## Bugs and issues

If you have found a bug on the site or have an idea for a new feature, feel free to [create a new issue](https://github.com/canonical-web-and-design/pythonoperatorframework.io/issues/new), or suggest a fix by [creating a pull request](https://help.github.com/articles/creating-a-pull-request/).


## Local development

The simplest way to run the site locally is using the [`dotrun`](https://snapcraft.io/dotrun) snap:

```bash
dotrun
```

Once the server has started, you can visit <http://127.0.0.1:8047> in your browser. You can stop the server using `<ctrl>+c`.

## License

The content of this project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying code used to format and display that content is licensed under the [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd](http://www.canonical.com/).


With ♥ from Canonical
