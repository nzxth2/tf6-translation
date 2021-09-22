# tf6-translation
English Patch for Yu-Gi-Oh! 5D's Tag Force 6 + translation tools

## Usage Notes
### EHP Packer
Unpacks and repacks EHP archives. Load an EHP archive first with the "Load File" button. While an EHP archive is loaded, you either  
a) press the "Unpack" button to extract the contents of the EHP archive to a directory of your choice  
b) press the "Repack" button to choose a directory that you want to reinsert into the EHP archive  
WARNING: If you try to use this tool on EHP files that have been modified by Clickclaxer01 aka Screw_the_Rules, it's very likely that it will fail to extract the contents properly. Some files may appear cut-off, because the offsets and file sizes have not been adjusted properly when the file was modified, from what I could tell. For best results, always use the original EHP files from the japanese ISO.

### StrTbl converter
Converts strTbl binary files into readable text files and vice versa.  
Make sure you don't change the number of lines in the resulting .txt file. In other words, do not remove or add any lines, not even empty ones.

### Story Rebuilder
When you launch the program, you get to choose which .txt file you want to reinsert into the story_scr_j_Old.ehp file.  
The resulting ehp file is generated in the "Algo Ehp" directory.  
Two story scripts have been included: the original japanese script provided by Omarrrio and the proper english translation script provided by me.

## Credits
Proper English translation + tools by nzxth2  
Story Rebuilder provided by Omarrrio
