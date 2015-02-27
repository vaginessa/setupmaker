DCP Setup Maker
===============
Powerful cross-platform install builder 

Great and powerful application to generate stable and multi-platform java installers.  

Watch a demo of DCP Setup Maker's installer being made in 2 minutes: https://www.youtube.com/watch?v=dmF5Kyla7Hg

Its intuitive UI and exceptional ease of use makes it very easy to build complex installers with large amounts of files.
The whole process is done step by step through a wizard-like interface, filling in fields and setting up files to finally build your package.

*Required: Java 1.7 for DCP Setup Maker and Java 1.6+ for built packages*  
*Powered by Java, IzPack, Nuget, Apache Pivot, Apache Ant and Stax.*  


LICENSE
-------
Apache License

Version 2.0, January 2004

http://www.apache.org/licenses/

CHANGELOG
---------

*1.1.1*
+ New features:  
Nuget/Chocolatey process compiler;  
Conditions support for IzPack;  
- Enhancements:  
Code structure update;  
Validators debugging warnings;  
Multi lines clipboard copy of selected log lines;  
Back to factory setup data on undo with no modifications;  
Merge of dcp libs to one library;  
Add scan horizontal split panel to Workspace auto-saved data;  
Build mode and default build configurations added to workspace data;  
Build logs copy to clipboard from context menu;  
Apache Commons IO for file copy operations;  
CommandLine build includes app name and version in package file;  
* Bug fixes:  
Default empty target path was based on app data instead of setup data;  
Workspace configuration was always saved even when not modified;  
Save file extension correction on empty path;  
Pack install name validation was displaying a wrong debug message;  
SFTP data load generated exception on empty data;  
Workspace data was saved with edit flag on;  
Frames Singletons were not used as intended  

*1.1.0*
* Bug Fixes:  
Set tab listbox circular mode disabled;  
Packs tooltip text correction on empty area;  
Scan Packs TableView selection enabled;  
Expand/Collapse buttons fix for Java 8;  
Fixed Data initialization and load at startup;  
Tab Singletons initialize with instantiation;  
Scan on enabled selection didn't update packs list  
+ New features:  
Pack version property;  
New compilation system based on multiple compilers;  
Command Line compilation of dcp files  
- Enhancements:  
Apache Pivot update to 2.0.4;  
Split panel on Scan tab's side bar;  
Resizable RegExp filter input size;  
Version extract from pack file name  


*1.0.3*
* Bug Fixes:  
Fixed for Java 8;  
Code structure update;  
Simple scan didn't update on changed selection;  
Filters now are enabled when selected;  
Version increment format check + focus  
+ Enhancements:  
GUI update;  
Assistant update;  
Recent scanned directories display with parent + full path on tooltip;  
Improved filtering system;  
Custom filters show up in UI;  
Second custom filter replaced with regexp filtering;  
Packs tooltip displays full path to pack on disk;  
Automated version number parts selection;  
Version Increment applies to selected part or last part by default  


*1.0.2*
- Bug fixes
- Custom user defined langpack
- Hidden pack option
- Pack Shortcut advanced options for folders and archives
- Suggestions for folder/archive inner files' paths shortcuts
- Packs source path included into save/load
- Path Validator for scanned folder path
- Scanned folder path can now be saved as default configuration
- Changing/Correcting pack paths from Scan folder path if path error
- Editing invalidated source path doesn't scan the folder
- Added DCP version number to save-file for future versions load fix
- Multiple comma separated authors can be added (emails included)
- Helper assistant text updated
- Added Tera-Bytes to split size units
- Packs panel disabled if all packs are required
- Shortcuts panel disabled if no shortcut to install
- Log line selection copies content to clipboard
- Packs can be deleted from Set tab
- Increment version number button


*1.0.1*
- Bug fixes
- Fixed for Mac OS X based systems
- Apache Pivot library updated from 2.0.2 to 2.0.3
- Tweak option for automated script generation at end of setup
- Input validation for file paths
- Process panel fixed for non-windows os
- Added support for more executable file types (reg, bat, sh, jar)
- Dependency implemented for executable packs
- Packs can have two types of dependency (Group or single Pack)
- Two Custom filters added to scan for advanced users
- Platform OS option for Packs
- Selected option by default for Packs
- HTTP Web Setup builder
- SFTP connection + packs file transfer
- Directories filter enabled for Recursive Scan
- Group rename function button added