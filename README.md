# RE_MSG
 010 Editor Binary Template for editing RE Engine msg files with `GMSG` struct. Aims to work on all versions of msg file across different RE Engine game.

# Installation
1. Download via "Code -> Download as ZIP"
2. Extract all to the same folder
3. In 010 Editor, Templates -> View Installed Templates
4. Install the bt file

# Usage
1. Open msg file with 010
2. Run the `RE_MSG.bt` template. Click `No` when it ask you if the file been decrypted.
3. Run the `RE_MSG_proc.1sc` script, make sure the bottom `decrypt();` line wasn't commented out. The file should be decrypted after "Script executed successfully." shown on the output panel.
4. Run the `RE_MSG.bt` template again. Click `Yes` when it ask you if the file been decrypted. Finish.

Tips: Choose `View`->`Character Set`->`UTF-8` to browse non-ascii character (although the encoding is utf-16)

## Encrypt back before save
Run the `RE_MSG_proc.1sc` script, make sure the bottom `encrypt();` line wasn't commented out (and make sure `decrypt();` line was commented out like `\\decrypt();`). The file should be encrypted after "Script executed successfully." shown on the output panel.

## Language Name 
Language Name by index value [LanguageEnum](LanguagesEnum.md)

## File editing
Try [REMSG_Converter](https://github.com/dtlnor/REMSG_Converter) - Python library for converting from RE engine msg text file to json/csv/txt and back.

# Credits
* wwylele's [mhrice](https://github.com/wwylele/mhrice), for file structure.
* ponaromixxx's [msg tool](https://zenhax.com/viewtopic.php?f=12&t=13337), for file structure.

* alphazolam's [RE_RSZ](https://github.com/alphazolam/RE_RSZ), for functions I just copy paste to my script.
