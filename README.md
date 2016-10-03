Supported tags and respective `Dockerfile` links
================================================

  * [`latest`](https://github.com/wernight/docker-codebox/blob/master/Dockerfile) latest public (as described here) [![](https://images.microbadger.com/badges/image/wernight/codebox.svg)](http://microbadger.com/images/wernight/codebox "Get your own image badge on microbadger.com")


What is Codebox?
================

[Codebox](https://github.com/CodeboxIDE/codebox) is a complete and modular Cloud IDE. It is an open source component of [codebox.io](https://www.codebox.io/) (Cloud IDE as a Service)


How to use this image
=====================

**This is currently an alpha version. It is not yet up to my Docker images standard.**

    $ docker run -d -p 8080:80 wernight/codebox

Wait a few seconds and open `http://localhost:8080/` in your browser.

You probably want to mount `/workspace` somewhere locally to persist it.


User Feedback
=============

Having more issues? [Report a bug on GitHub](https://github.com/wernight/docker-codebox/issues).