python-libtorrent for Kodi
==================
script.module.libtorrent is a Kodi module that makes easy import of the python
bindings of [libtorrent](https://www.libtorrent.org/).

This version of the add-on is based on [DiMartinoXBMC
version](https://github.com/DiMartinoXBMC/script.module.libtorrent) but with
the following differences:
* the version 1.1.11 was compiled with OpenSSL (to support HTTPS links) for
  MacOS and linux_armv7
* the other versions (which do not support HTTPS) for MacOS and linux_armv7
  were removed

The goal was to allow the [PeerTube
add-on](https://framagit.org/StCyr/plugin.video.peertube) to be installed on
JeOS systems like LibreELEC.

Please have a look to the [wiki](../../wiki) for more information (including
status of the library for each system).

# Usage

Add this line in the node `requires` of the addon.xml file:
```python
<import addon="script.module.libtorrent" version="X.Y.Z"/>
```

Then import libtorrent in the add-on code with:
```python
from python_libtorrent import libtorrent
``` 

# License

MIT License