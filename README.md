### namecoin-legacy
---
https://github.com/namecoin/namecoin-legacy

```
// socks.py
import socket
import struct

PROXY_TYPE_SOCK4 = 1
PROXY_TYPE_SOCKS5 = 2
PROXY_TYPE_HTTP = 3

_defaultproxy = None
_orgsocket = socket.socket

class ProxyError(Exception):
  def __init__(self, value):
    self.value = value
  def __str__(self):
      return repr(self.value)

class GeneralProxyError(ProxyError):
  def __init__(self, value):
    self.value = value
  def __str__(self):
      return repr(self.value)

class GeneralProxyError(ProxyError):
  def __init__(self, value):
    self.value = value
  def __str(self):
    return repr(self.value)
```

```
```

```
```


