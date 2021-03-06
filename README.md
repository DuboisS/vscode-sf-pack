# vscode-sf-pack
sf-pack is a simple pack of extensions for symfony developers.

[https://marketplace.visualstudio.com/items?itemName=duboiss.sf-pack](https://marketplace.visualstudio.com/items?itemName=duboiss.sf-pack)

## Extensions
- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client) - Full of essential features for productive PHP development.
- [PHP Getters & Setters](https://marketplace.visualstudio.com/items?itemName=phproberto.vscode-php-getters-setters) - Generate getters and setters with one single command.
- [Symfony code snippets And Twig Support & Yaml](https://marketplace.visualstudio.com/items?itemName=nadim-vscode.symfony-code-snippets) - Symfony snippets. Twig & Yaml support.
- [Symfony Console Run All Symfony Commands](https://marketplace.visualstudio.com/items?itemName=nadim-vscode.symfony-super-console) - Run all Symfony commands from VSC ui
- [Symfony for VSCode](https://marketplace.visualstudio.com/items?itemName=TheNouillet.symfony-vscode) - Provide basic autocompletion and visualization of the Symfony container.
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) - .env syntax highlighting.
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) - Provides comprehensive YAML Language support.

## Configuration
### Symfony code snippets And Twig Support & Yaml
Use snippets in annotations.

settings.json
```json
    "editor.quickSuggestions": {
        "other": true,
        "comments": true,
        "strings": true
    }
```
### Symfony Console Run All Symfony Commands
change the console path

settings.json
```json
    "superConsole.path": "your console path default is php bin/console"
```

## Changelog
See the [changelog](https://github.com/DuboisS/vscode-sf-pack/blob/master/CHANGELOG.md) for releases notes.
