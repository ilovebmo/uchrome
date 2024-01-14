# 🔥uchrome: Modular Firefox Customization🦊

Modular approach to Firefox CSS.

This repo contains components and themes, as well as a userContent.css file, that are then imported into the **userChrome.css** file. There should _NEVER_ be a need to edit any file other than **userChrome.css**.

To select the components or themes you want, simply add or remove their respective `@import` from the **userChrome.css** file.

## 📦Components

- **_Disappearing Bar_**.
- **_One-line Firefox_**, based on [One-line Firefox](https://github.com/khuedoan/one-line-firefox).
- **_Bottom bar_**, partly adapted from [Arty2's _tabs_to_bottom_](https://github.com/Arty2/userstyles/blob/master/tabs_to_bottom.userchrome.css).

## 🖌️Themes

- **_arcadia_**, adapted from [arcadia](https://github.com/tyrohellion/arcadia).

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
