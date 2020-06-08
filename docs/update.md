# How  to update your Orange PI

## Debian (and Debian-derived distributions)
#

First, ensure that all distribution repositories are up to date, with the following command:

```sudo apt update ```

You will be prompted at this point for your sudo password, like this:

```
[sudo] password for Saoirse:
```

Please note:
* you will *not* receive feedback while typing your sudo password; this is normal.
* the default password (for most orange pi images) is `orangepi`, while for armbian, it is `1234` (though you would have been prompted to change this on first boot). Others may differ; please refer to your distribution's documentation.



#

Once the list of repositories has been updated, you may see something like:

```
3 packages can be upgraded. Run 'apt list --upgradable' to see them.
```

This indicates that updates are available, just as it says. To install them, run the following:
```sudo apt dist-upgrade ```

Depending on your configuration, you may be asked for your sudo password again. To change this setting, see [user management aud sudo](users.md).

