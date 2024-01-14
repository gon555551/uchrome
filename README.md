# 🔥uchrome: Modular Firefox Customization🦊

Modular approach to Firefox CSS.

This repo contains components and themes that are imported into the **userChrome.css** file, as well as a userContent.css file. There should never be a need to edit any file other than **userChrome.css**, but of course you can tweak any file to your liking! I don't take responsibility if anything breaks though~

To select the components or themes you want, simply add or remove their respective `@import` from the **userChrome.css** file.

## 📦 Components

- **_Disappearing Bar_**.
- **_One-line Firefox_**, based on [One-line Firefox](https://github.com/khuedoan/one-line-firefox).
- **_Bottom bar_**, partly adapted from [Arty2's _tabs_to_bottom_](https://github.com/Arty2/userstyles/blob/master/tabs_to_bottom.userchrome.css).

## 🖌️ Themes

- **_arcadia_**, adapted from [arcadia](https://github.com/tyrohellion/arcadia).
- **_Firefox-ONE_**, adapted from [Firefox-ONE](https://github.com/Godiesc/firefox-one).

## 🎒 Pre-requisites

All components and themes are designed for Firefox with Compact mode enabled.

1. Visit the `about:config` page;  
   1.1 Search for and set `browser.compactmode.show` to <font color=green>true</font>.
2. Right click on the toolbar and select **Customize Toolbar**;  
   2.2. Set the density as `Compact`.

## 🔧 How to use

In `about:config`:

- Set `toolkit.legacyUserProfileCustomizations.stylesheets` to <font color=green>true</font>.
- Set `extensions.pocket.enabled` to <font color=red>false</font>.

The path to your Firefox profile is available at `about:profiles`.

```shell
cd "path/to/firefox/profile"
git clone https://github.com/gon555551/uchrome chrome
```

## 👹 Limitations

There's no guarantee that components or themes won't clash with each other.

- Themes are larger projects so it's best to leave them last in the **userChrome.css** file to improve compatibility.
- Additionally, I provide some compatibility files for certain components.

Themes may require specific files other than **userChrome.css** to be edited, certain extensions to be installed, or certain settings to be turned on or off.

- I try to go around this, but sometimes it's not possible. **_Always check the official repo for the themes to see their specific requirements_**.

These components and themes may not work for all versions of Firefox.
