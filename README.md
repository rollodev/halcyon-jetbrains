<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/14093-halcyon-theme">
    <img alt="Halcyon Logo" src="https://raw.githubusercontent.com/ADMARIl/halcyon-jetbrains/master/docs/pluginIcon.png" width="135" />
  </a>
</p>
<h1 align="center">
  Halcyon Theme for JetBrains
</h1>
<p align="center">
  A minimal, dark blue theme for the JetBrains suite of IDEs based on <a href="https://github.com/bchiang7/halcyon-vscode">Brittany Chiang's VSCode theme</a>.
</p>
<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/14093-halcyon-theme">
    <img alt="Version" src="https://img.shields.io/jetbrains/plugin/v/14093-halcyon-theme" />
  </a>
  <a href="https://plugins.jetbrains.com/plugin/14093-halcyon-theme">
    <img alt="Downloads" src="https://img.shields.io/jetbrains/plugin/d/14093-halcyon-theme" />
  </a>
</p>

![code](docs/screenshots/main_shadow.png)
*Due to the way JetBrains handles syntax highlighting, there are some slight differences in coloring from the original.*

## Updates
Unfortunately, I no longer use JetBrains IDEs in my day-to-day work so I don't have as much time to keep this plugin updated; however, I still do update occasionally! **Please feel free to contribute if there is an issue I haven't gotten to yet!**

## Installation via JetBrains

1. Open the **Plugins** panel in your IDE. `File → Settings → Plugins`
2. Search for `Halcyon Theme`
3. Click **Install** to install it
4. Click **Ok** to apply the changes
5. Restart the IDE when prompted
6. If the theme isn't automatically chosen, go to `File → Settings → Appearance & Behavior → Appearance → Theme →` **Halcyon**

![settings](docs/screenshots/settings_shadow.png)

## Manual Installation

Read the [JetBrains Support Page](https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_disk)

## Updating (or if the theme suddenly turns itself off)

While the IDE should prompt you when an update is available, there is occasionally an issue where the theme isn't applied after an update
1. To fix this, go to `File → Settings → Editor → Color Scheme` and ensure **Halcyon** is selected under the `Scheme` dropdown.
2. Next, ensure **Halcyon** is selected under `File → Settings → Appearance & Behavior → Appearance → Theme`
3. If the previous two steps didn't fix your issue, try restarting your IDE; otherwise, please [open an issue](https://github.com/ADMARIl/halcyon-jetbrains/issues).

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://via.placeholder.com/10/c3a6ff?text=+) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://via.placeholder.com/10/ffd580?text=+) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://via.placeholder.com/10/ffae57?text=+) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://via.placeholder.com/10/a2aabc?text=+) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#171c28](https://via.placeholder.com/10/171c28?text=+) `#171c28` | Workbench background                       |
| ![#1d2433](https://via.placeholder.com/10/1d2433?text=+) `#1d2433` | Editor background                          |
| ![#2f3b54](https://via.placeholder.com/10/2f3b54?text=+) `#2f3b54` | Highlight, widgets, panels                 |
| ![#6679a4](https://via.placeholder.com/10/6679a4?text=+) `#6679a4` | Dividers, subtle UI elements               |
| ![#8695b7](https://via.placeholder.com/10/8695b7?text=+) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://via.placeholder.com/10/ffcc66?text=+) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://via.placeholder.com/10/ef6b73?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Modified highlights                        |

## Changelog

See the changelog [here](docs/CHANGELOG.md).

## Please Consider Contributing!

- I know I haven't covered all the languages. Please feel free to contribute!
Pull requests are always welcome. For major changes, please open an issue first to discuss what you would like to change.
- Have change or addition you'd like to see? Open an issue!

## License

[MIT](https://choosealicense.com/licenses/mit/)


###### Many thanks to [Brittany Chiang](https://github.com/bchiang7) whose existing theme for VS code was the inpiration for this project.
