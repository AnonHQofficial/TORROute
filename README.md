# TORRoute

#### Install on Kali/Debian

First we need to install pip3 for python3 dependencies:

```$ sudo apt-get install python3-pip```

Then we can run through dependency checks:

```$ pip3 install -r requirements.txt```

#### Usage

To run a scan against a target:

```python3 TORROute.py --target seo.com```

To run a scan against a target using Tor:

```service tor start```

(or if you are using Windows or Mac install vidalia or just run the Tor browser)

```python3 TORROute.py --target seo.com --tor```

> Please make sure you are running with Python3 and not Python2.*.


#### Dependencies
**Python3**
* argparse
* colorama
* socket
* binascii
* datetime
* requests
* win_inet_pton
