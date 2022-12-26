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

## Language Name 
Language Name by index value [LanguageEnum](LanguagesEnum.md)

# Credits
* wwylele's [mhrice](https://github.com/wwylele/mhrice), for file structure.
* ponaromixxx's [msg tool](https://zenhax.com/viewtopic.php?f=12&t=13337), for file structure.

* alphazolam's [RE_RSZ](https://github.com/alphazolam/RE_RSZ), for functions I just copy paste to my script.
