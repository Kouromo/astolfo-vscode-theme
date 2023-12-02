# Astolfo Color Theme Extension for Visual Studio Code

## Overview

The Astolfo extension for Visual Studio Code is designed to bring a touch of pink to your coding environment. Embrace a softer color palette and create a coding space that reflects your style. Infuse your coding experience with a touch of femboy aesthetics.

## How to Add the Astolfo Wallpaper

To set up the Astolfo wallpaper in Visual Studio Code, follow these steps:

1. Begin by installing the extension from the Visual Studio Marketplace: [Background Extension](https://marketplace.visualstudio.com/items?itemName=shalldie.background). After installation, restart Visual Studio Code.

2. Locate the complete path of the AstolfoBackground.png image within the extension directory. You can find it at `.vscode\extensions\kouromo-theme.astolfo-theme-0.2.0\images\AstolfoBackground.png`.

3. Open your Visual Studio Code `settings.json` file and add the following code snippet:

```json
"background.enabled": true,
"background.useFront": false,
"background.style": {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "z-index": "99999",
    "height": "100%",
    "margin-left": "30%",
    "background-position": "right",
    "background-size": "cover",
    "background-repeat": "no-repeat",
    "opacity": 0.3
},
"background.customImages": [
    "file:///PATH_TO_THE_FOLDER/.vscode/extensions/kouromo-theme.astolfo-theme-0.2.0/images/AstolfoBackground.png"
],
```

- Replace the file path in "background.customImages" with the full path to your AstolfoBackground.png image. Save the file, and you should now have the Astolfo-themed wallpaper in your Visual Studio Code environment.

## Screenshot

![Demo of the theme](https://raw.githubusercontent.com/Kouromo/astolfo-vscode-theme/main/images/demo.png)

![Demo of the theme](https://raw.githubusercontent.com/Kouromo/astolfo-vscode-theme/main/images/demo1.png)

**Note**: The Astolfo background image was sourced from [DeviantArt](https://www.deviantart.com/iyunlock/art/Astolfo-Fate-Render-875931083).
