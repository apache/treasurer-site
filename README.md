# Apache Treasurer

[Apache Treasurer](https://treasurer.apache.org/)

This repository provides the website and source code for The Apache Software Foundation office of the Treasurer.

- [Pages](content/pages) -- website pages in GitHub Markdown
- [Issues](https://github.com/apache/treasurer-site/issues) -- tracker

The website is built with [Pelican](https://blog.getpelican.com).
CI/CD is via a [.asf.yaml file](https://cwiki.apache.org/confluence/display/INFRA/Git+-+.asf.yaml+features).

- [Template](theme/apache/templates) -- simple html template (inline css)
- [Images](content/images) -- logo and other images
- [Pelican Configuration](pelicanconf.py) -- pelican configuration
- [ASF YAML build](.asf.yaml) -- ASF infrastructure instructions

See the [Developer Guide](DEVELOPER.md) for details about GitHub actions, frameworks, and other tooling.
