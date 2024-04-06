# Install Debloater for Crysis Remastered

This template is designed to work with Dishonored - Definitive Edition. Should work with all versions of the game and was tested on the GOG version. 
- Removes unused languages files (aka "Localizations").
- Removes the redist folder. Make sure to run the game at least once. 
- Removes the startup movies. 

Expected saving: ~27% (~5-6GB)

## Installation

[Download](https://github.com/neatodev/InstallDebloater/blob/main/templates/DISHONORED/DISHONORED.zip) and put the folder next to InstallDebloater.exe. Run the program either through PowerShell/Commandline or using the provided batch file.

## Usage

First, open DISHONORED.ini with a text editor and add the complete filepath to your game root folder (example: C:\Steam\steamapps\common\Crysis Remastered).

For both commandline and batch methods, use the following syntax:

```bash
.\InstallDebloater.exe DISHONORED\DISHONORED.ini
```
This will run the script.
If you want to keep some languages, take a look at the DISHONORED_NAMING_SCHEME.txt and DISHONORED_FOLDER.txt templates. All languages are isolated, just comment the lines related to the language(s) you want to keep. 

## Contributing
You are welcome to contribute by making your own templates or improve existing ones. However, please make sure you're not trying to delete critical files. 