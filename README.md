
Linux Kernel Powerball Module
=============================

A simple Linux Kernel module for getting a [Powerball](http://www.powerball.com/)<sup>TM</sup> Lottery "quick pick".


PREREQUISITES
-------------

Install Linux Kernel headers and source or a [custom Linux Kernel](http://gregdonald.com/articles/how-to-build-latest-linux-kernel-from-linus-git-repo-on-debian-ubuntu/).


INSTALL
-------

```bash
make
```

```bash
insmod powerball.ko
```


USAGE
-----

```bash
cat /dev/powerball
```
> 12 23 34 45 56 17
