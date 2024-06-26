# Install Debloater for The STAR WARS: The Force Unleashed Ultimate Sith Edition

This template is designed to work with STAR WARS: The Force Unleashed Ultimate Sith Edition. Should work with all versions of the game and was tested on the Steam version. 
- Removes all languages except English.
- Removes intro movies
- Removes the Redist folder

## Installation

[Download](https://github.com/neatodev/InstallDebloater/blob/main/templates/STAR_WARS_THE_FORCE_UNLEASHED/STAR_WARS_THE_FORCE_UNLEASHED.zip) and put the folder next to InstallDebloater.exe. Run the program either through PowerShell/Commandline or using the provided batch file.

## Usage

First, open STAR_WARS_THE_FORCE_UNLEASHED.ini with a text editor and add the complete filepath to your game root folder (example: C:\Steam\steamapps\common\Star Wars The Force Unleashed).

For both commandline and batch methods, use the following syntax:

```bash
.\InstallDebloater.exe STAR_WARS_THE_FORCE_UNLEASHED\STAR_WARS_THE_FORCE_UNLEASHED.ini
```
This will run the script.
If you want to keep some languages, take a look at the STAR_WARS_THE_FORCE_UNLEASHED_NAMING_SCHEME.txt and template. All languages are isolated, just comment the lines related to the language(s) you want to keep. 

## Contributing
You are welcome to contribute by making your own templates or improve existing ones. However, please make sure you're not trying to delete critical files. 