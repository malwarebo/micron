# Micron

* This is a developer build of chromium version 89.0.4341.0 (x86_64).

* The browser is under initial development. 


# Usage


* Build this version

```
cd micron/chromium/src
autoninja -C out/Default chrome
```

* Run without building

``` 
cd micron/chromium/src
out/Default/Chromium.app/Contents/MacOS/Chromium
```

* Avoiding the “incoming network connections” dialog

```
out/Default/Chromium.app/Contents/MacOS/Chromium --disable-features=“MediaRouter”
```
