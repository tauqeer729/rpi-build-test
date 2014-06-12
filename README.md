notro/rpi-build-test
==========

Linux kernel release 3.15.0+ with builtin IPv6 support for the Raspberry Pi.

Install
-------

```text
sudo REPO_URI=https://github.com/notro/rpi-build-test BRANCH=latest rpi-update
```



Changelog
---------
No changes, first release.


Sources
-------
* [raspberrypi/tools](https://github.com/raspberrypi/tools/archive/108317fde2ffb56d1dc7f14ac69c42f34a49342a.tar.gz)
* [raspberrypi/firmware](https://github.com/raspberrypi/firmware/archive/e45a4a25cd6ec19912de3310194ebaf8f02676f6.tar.gz)
* [raspberrypi/linux](https://github.com/raspberrypi/linux/archive/959a708cea1c7e044032bd7e904e72dcf0a51db4.tar.gz)


Patches
--------
None

Kernel config
-------------
Default config: bcmrpi_defconfig



Changed:
```text
IPV6 m -> y
```


<p align="center">Built with <a href="https://github.com/notro/rpi-build/wiki">rpi-build</a></p>
