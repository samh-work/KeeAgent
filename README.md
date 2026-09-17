<img align="right" src="doc/images/logo.png">

KeeAgent is a plugin for KeePass 2.x. It allows other programs to access SSH
keys stored in your KeePass database for authentication. It can either act as a
stand-alone agent or it can interface with an external agent.

### Local changes

This customized version is based on KeeAgent v0.13.8. **Alt+A** loads SSH keys
from the selected entries, including search results. The group-loading command
has no keyboard shortcut, preventing accidental group loads through Ctrl+M.
**Ctrl+Shift+A** opens the KeeAgent manager, the same as Tools > KeeAgent.
The group menu command and Ctrl+Shift+M to load a key and open its URL remain
available. Official KeeAgent updates do not include this customization.


DOWNLOAD
--------

#### Official release

Get the latest stable official release of KeeAgent at <https://lechnology.com/software/keeagent>.

#### Chocolatey 📦

You can [use Chocolatey to install](https://community.chocolatey.org/packages/keepass-plugin-keeagent#install) it in a more automated manner:

```
choco install keepass-plugin-keeagent
```

To [upgrade KeePass Plugin KeeAgent](https://community.chocolatey.org/packages/keepass-plugin-keeagent#upgrade) to the [latest release version](https://community.chocolatey.org/packages/keepass-plugin-keeagent#versionhistory) for enjoying the newest features, run the following command from the command line or from PowerShell:

```
choco upgrade keepass-plugin-keeagent
```


USAGE
-----

Documentation is at https://keeagent.readthedocs.io/en/latest/


HACKING
-------

Pull requests are welcome! See [HACKING.md](./HACKING.md) for more info.


COPYRIGHT
---------

(C) 2012-2024 David Lechner <david@lechnology.com>
