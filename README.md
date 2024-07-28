# Local Wordpress Flatpak

## Building

```
flatpak-builder build-dir --user --ccache --force-clean --install com.localwp.Local.yml
```

Then you can run it via the command line:

```
flatpak run com.localwp.Local
```

or just search for the installed app on your system
