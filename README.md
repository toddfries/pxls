# pxls
perl X listing app

pxls    # list any X app with any atom (xlsclient only lists WM_COMMAND apps)

pxls -a # show attributes too

pxls -A # show all apps even ones without atoms

pxls -e # show X extensions

e.g.

```
$ pxls | head
QueryTree(1946)
|- Window 0x    600011:
|  	 WM_LOCALE_NAME   (313) <C>
|  	 WM_CLASS         ( 67) <xconsole>, <XConsole>
|  	 WM_CLIENT_MACHINE( 36) <xxxxxxx.xxxxx.xxx>
|  	 WM_COMMAND       ( 34) </usr/X11R6/bin/xconsole>, <-geometry>, <480x130-0-0>, <-daemon>, <-notify>, <-verbose>, <-fn>, <fixed>, <-exitOnFail>
|  	 WM_ICON_NAME     ( 37) <xconsole>
|  	 WM_NAME          ( 39) <xconsole>
|- Window 0x    a0000c:
|  	 WM_LOCALE_NAME   (313) <en_US.UTF-8>
```
