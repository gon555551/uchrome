# 🔥uchrome: Firefox One-line+🦊

All of Firefox in a single line.

![What it looks like (using Mercury)](https://i.postimg.cc/jSRnLDVz/image.png)
![With the bar disabled](https://i.postimg.cc/G3DDJtvT/image.png)

## 🎒 Pre-requisites

This [userChrome.css](https://github.com/gon555551/uchrome/blob/master/userChrome.css) file is designed for Firefox with Compact mode enabled. To do this, follow the steps below.

**1.** Visit the `about:config` page;  
**1.1** Search for and set `browser.compactmode.show` to <font color=green>true</font>.  
**2.** Right click on the toolbar and select **Customize Toolbar**;  
**2.2.** Set the density as `Compact`.


## 🔧 How to use

In ``about:config``:  
- Set ``toolkit.legacyUserProfileCustomizations.stylesheets`` to <font color=green>true</font>.
- Set ``extensions.pocket.enabled`` to <font color=red>false</font>.

The path to your Firefox profile is available at `about:profiles`.

```
cd "path/to/firefox/profile"
git clone https://github.com/gon555551/uchrome chrome
```

*When resizing the window, the bar can't be recovered with the mouse. Enter fullscreen mode (F11) and it'll work again.*
***
> Based on [One-line Firefox](https://github.com/khuedoan/one-line-firefox) by [khuedoan](https://github.com/khuedoan).