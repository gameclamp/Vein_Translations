# Vein_Translations
This project is used for the Vein game translation workflow. After updating Game.locres_*.csv files, they will be automatically packaged as pak files.

## Usage
Place the pak file in Vein\Vein\Content\Paks folder.

## Pull requests welcome
CSV files can be edited online or offline using a regular text editor. If using Excel, you need to save as UTF-8-BOM first to make Excel read it as UTF-8.

### Translation Rules
* CSV files use English commas to separate 3 columns: first column is the key (cannot be changed), second column is the source English text, third column is the Translation (Chinese).
* Do not translate tags with <> and {}
* Do not translate settings like Low Medium High Custom, etc., as it will cause the page to not change when modifying settings.

## Credits
UE4LocalizationsTool: https://github.com/amrshaheen61/UE4LocalizationsTool

Repak: https://github.com/trumank/repak

Some translation from Vein Discord Server: https://discord.com/servers/vein-944307356693577799
