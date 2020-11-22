# <img src="https://raw.githubusercontent.com/Maurin3/vscode-miami-vibes/master/icon.png" width="30" height="30"> Miami Vibes

![preview](https://raw.githubusercontent.com/Maurin3/vscode-miami-vibes/master/media/preview.png)

## Installation

Clone this repository in the VSCode extensions directory :

* Windows :  `%USERPROFILE%\.vscode\extensions`
* Mac : `$HOME/.vscode/extensions`
* Linux : `$HOME/.vscode/extensions`

To clone this repository use this command:

`git clone https://github.com/Maurin3/vscode-miami-vibes.git`

## How do I enable the glow effect?
You need to install first the [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension which allows you to load custom CSS and JS. Please read the README file for that extension before continuing this installation. If there is any issue regarding the glow effect, check first if the Custom CSS and JS Loader is active.

Copy the file path below and add it to your VS code settings.json and replace `username` by your username.

On Mac:

```json
{
    "vscode_custom_css.imports": [
        "file:///Users/username/.vscode/extensions/vscode-miami-vibes/miami-vibes.css"
    ]
}
```

On Linux:

```json
{
    "vscode_custom_css.imports": [
        "file:///home/username/.vscode/extensions/vscode-miami-vibes/miami-vibes.css"
    ]
}
```
On Windows:

```json
{
    "vscode_custom_css.imports": [
        "file:///C:/Users/username/.vscode/extensions/vscode-miami-vibes/miami-vibes.css"
    ]
}
```
**Important:** Make sure you include the file protocol in the path i.e. `file://`

Then, open your command palette and choose "Enable custom CSS and JS" then restart you VSCode and it should be good :smile:

If VS Code pops up a message to say that it is corrupted, this is caused by the Custom CSS & JS extension and not the theme. As their installation instructions say, you can click "Don't show again" to dismiss the popup.

Note : The glow effect is based on the [Aylin Theme](https://github.com/AhmedAbdulrahman/aylin-vscode-theme) and adapted to this theme.