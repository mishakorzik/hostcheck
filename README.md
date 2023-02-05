## Usage

**A good tool for checking host, has 24+ servers from different countries to check. Using check-host.net**


### Save as file
```python
#save ping server data (ex. www.google.com)
>>> from hostcheck import *
>>> host.ping("www.google.com")
saved as: check-host.json
>>> 

#save http server data (ex. www.google.com)
>>> from hostcheck import *
>>> host.http("www.google.com")
saved as: check-host.json
>>> 

#save tcp server data (ex. 3.125.102.39:13352)
>>> from hostcheck import *
>>> host.tcp("3.125.102.39:13352")
saved as: check-host.json
>>> 

#save dns server data (ex. 1.1.1.1)
>>> from hostcheck import *
>>> host.dns("1.1.1.1")
saved as: check-host.json
>>>

```

### Preview data

```python

#view ping server data (ex. www.google.com)
>>> from hostcheck import *
>>> host.ping("www.google.com", True)

#view http server data (ex. www.google.com)
>>> from hostcheck import *
>>> host.http("www.google.com", True)

#view tcp server data (ex. 3.125.102.39:13352)
>>> from hostcheck import *
>>> host.tcp("3.125.102.39:13352", True)

how to view server data
video: https://youtu.be/DlUiGR1HfTU

```

**all results are automatically saved to the check-host file in json format.  You can read it using the json module.**

## Installation

```basb
pip install hostcheck

```

## Maybe will be in new versions

 - dns checker 
 - udp checker

