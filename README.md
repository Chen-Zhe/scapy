# Scapy with SSL/TLS support#

Hand integrated from [Scapy](https://github.com/secdev/scapy/) and [scapy-ssl_tls](https://github.com/tintinweb/scapy-ssl_tls) using the latest versions as of today (Dec 28, 2017). Works only on Python 3 (change one line's `.items()` to `.iteritems()` should help to run in Python 2)


## Installation ##

```
git clone -b with_ssl-tls https://github.com/chen-zhe/scapy
cd scapy
python setup.py install
>>>
```


### [](#tutorials)Tutorials ###

To begin with Scapy, you should check [the notebook
hands-on](doc/notebooks/Scapy%20in%2015%20minutes.ipynb) and the [interactive
tutorial](http://scapy.readthedocs.io/en/latest/usage.html#interactive-tutorial).
If you want to learn more, see [the quick demo: an interactive
session](http://scapy.readthedocs.io/en/latest/introduction.html#quick-demo)
(some examples may be outdated), or play with the
[HTTP/2](doc/notebooks/HTTP_2_Tuto.ipynb) and [TLS](doc/notebooks/tls)
notebooks.
