# anytype-install-and-update
A script to automate installing and updating Anytype via AppImage based on the same script for Joplin: https://github.com/laurent22/joplin/blob/dev/Joplin_install_and_update.sh

This will handle the `--no-sandbox` issue that modern (as of this writing) Ubuntu based distros face with AppImage releases.  For example, this sets up the KDE/plasma launcher and icon correctly, just like the Joplin one does.

# Usage
```
wget -O - https://raw.githubusercontent.com/draggor/anytype-install-and-update/main/Anytype_install_and_update.sh | bash
```

By default it will install the AppImage to `$HOME/.anytype/`.
