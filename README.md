# Places Indicator
**A GTK3 Menu Places Folder Indicator**

Quick access to Your Bookmarks in File manager.

<p align="left">
  <a href="https://appcenter.elementary.io/com.github.camellan.placesindicator"><img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter" /></a>
</p>

![Screenshot](https://raw.githubusercontent.com/camellan/placesindicator/master/data/images/placesindicator.png)

## Dependencies

Please make sure you have these dependencies first before building.

```
gtk+-3.0
glib-2.0
appindicator3-0.1
```
To build locally:

`meson build --prefix=/usr`

`cd build`

`ninja`

`sudo ninja install`