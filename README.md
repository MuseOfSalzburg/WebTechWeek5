# Learning HTML, CSS and JS

Description here....

## Folder Structure

```text
Root -+- index.html
      |
      +- README.md
      |
      +- about -+- index.html
      |
      +- assets -+- js -+-
                 |
                 +- css -+- site.css
                 |
                 +- img -+-
                 |
                 +- media -+-
```

## .gitignore

Create .gitignore with required file patterns
> Use the plugin .ignore in JetBrains IDEs
> 
> `CTRL`+`ALT`+`S` (Windows) to open settings
> 
> Click the Plugins option on the left side
> 
> Click on Marketplace and search for .ignore plugin
> 
> Locate the option and click install
> 
> Click OK when all required plugins are installed
> Sometime the IDE will need to restart to apply the changes

## .keep
This file is used to force folders that are empty to be committed

Add to any folder you need to be added to version control but may not be using immediately

Create it as a new text file with the filename `.keep`.
 
## Useful Plugins
- .ignore
- CSV
- Rainbow Brackets
- Indent Rainbow
- JSON Helper
- Markdown Editor
- Paste Images into Markdown
- Zero Width Character Locator
- Yet another emoji support
- GitToolBox
- Extra ToolWindow Colorful Icons

## Useful Commands

### Make  Directory/Folder
In DOS command line:
```shell
mkdir folder_name
```
DOS Example:
```shell
mkdir assets assets\img assets\js assets\css assets\media
mkdir about
```
Linux example:
```shell
mkdir -p assets\{img,js,media,css} about
```
