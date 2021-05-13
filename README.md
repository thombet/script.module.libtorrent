python-libtorrent for Kodi
==================
script.module.libtorrent is a Kodi module that makes easy import of python-libtorrent

This version of the add-on is based on [DiMartinoXBMC initial version](https://github.com/DiMartinoXBMC/script.module.libtorrent).

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