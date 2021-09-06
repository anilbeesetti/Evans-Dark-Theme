# Evans Dark Theme For VScode

[![Version](https://vsmarketplacebadge.apphb.com/version/anilbeesetti.evans-dark-theme.svg)](https://marketplace.visualstudio.com/items?itemName=anilbeesetti.evans-dark-theme)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/anilbeesetti.evans-dark-theme.svg)](https://marketplace.visualstudio.com/items/anilbeesetti.evans-dark-theme)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/anilbeesetti.evans-dark-theme.svg)](https://marketplace.visualstudio.com/items/anilbeesetti.evans-dark-theme)

## A new stunning dark theme for VScode

Dark is the new Light...

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Evans Dark Theme` - find the one by **AnilBeesetti**
3. Click **Install** to install it.
4. Code > Preferences > Color Theme > **Evans Dark Theme**

## Preview

### Default Theme

![Screenshot_20210427_112456](https://user-images.githubusercontent.com/66936649/116194628-b7ed4500-a74e-11eb-9d6d-98859c65861f.png)
![Screenshot_20210427_112512](https://user-images.githubusercontent.com/66936649/116194638-bb80cc00-a74e-11eb-85c5-5dad3f6d7b7a.png)

### Terminal

![Screenshot_20210427_112350](https://user-images.githubusercontent.com/66936649/116194298-49a88280-a74e-11eb-90d2-fd4e5953e90e.png)
![Screenshot_20210427_112543](https://user-images.githubusercontent.com/66936649/116194643-bd4a8f80-a74e-11eb-8f66-2d87b985bfca.png)

## Recommended Settings

These Settings will improve theme a bit more.
Follow the steps below to set recommended settings.

1. Open run `View → Command Palette`
2. Search for `Open Settings (JSON)` and open it. It will open a `settings.json` file
3. Copy the JSON below and paste it in `settings.json` file

```js
{
  // save this settings along with your personal settings
  "workbench.colorTheme": "Evans Dark Theme",
  // Caskaydia Cove font is recommeded, Which is free
  // You can get it from https://github.com/eliheuer/caskaydia-cove
  "terminal.integrated.fontFamily": "'Caskaydia Cove', 'Iosevka'",
  "editor.fontFamily": "'Caskaydia Cove', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.formatOnSave": true,
  "window.menuBarVisibility": "compact",
}
```

## Customization

If you are using VSCode 1.12+ versions you can customize the colors to your liking, overriding the ones provided by this theme. More info [here](https://code.visualstudio.com/docs/getstarted/theme-color-reference).

### Custom Font

The original Evans dark theme does not use a custom font, for that reason I don't supply a custom font either, but you might be used to see screenshots of the Evans Dark theme using the [Caskaydia Cove](https://github.com/eliheuer/caskaydia-cove) font. You can easily [customize your settings](https://code.visualstudio.com/docs/getstarted/settings) to use it.  
If you download and install the font in your system, you can add this option to have a custom font:

```json
{
  "editor.fontFamily": "YOUR FONT, Menlo, Monaco, 'Courier New', monospace"
  // Caskaydia Cove font is recommended.
}
```

## Contributing

To work on the theme:

1. Clone this repo and open in VS Code
2. Open run `View → Run`
3. Click `Launch Extension`. This will open up another VS Code Editor
4. Make changes to `evans-dark-theme.json`. You will see changes reflected in the other editor that opened in step 3.

If you are making a Pull Request, Please Expain what you have done breifly and give me a screenshot of before/after!
