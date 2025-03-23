# NIKKE Character Swapper
A simple tool useful to mod [NIKKE](https://nikke-en.com/) bundles. Thanks to Bingle and Danieru for the help.

### NOTE: The character swapper works to swap any character over any other character. You can swap special cases (Marciana skin/Evangelion skins/Mast Diver skin) over other characters, but it doesn't work if you want to swap other characters over the mentioned special cases (Marciana skin/Evangelion skins/Mast Diver skin). Same case applies for standing Guillotine Winter Slayer, Mast Romantic Maid, Anchor Innocent Maid and Helm skin 02 to put some examples.

## Source code:

The .exe file is a SFX file created with WinRAR that contains all of the Python scripts and JSON files needed, it can be extracted with WinRAR/7Zip.


## Before to use this tool:

  - Download and install [.NET SDK 8](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.404-windows-x64-installer).
  - Download and install [Python](https://www.python.org/downloads/), along with all of the addons included (pip, etc).
  - Download and install [Microsoft C++ Build Tools](https://aka.ms/vs/17/release/vs_BuildTools.exe), and after that install the necessary libraries following [this video](https://files.catbox.moe/vqsuix.mp4).

  - Open a Windows PowerShell window as Admin, type: pip install UnityPy. And hit enter to install UnityPy for Python.
  - On the same PowerShell window type: pip install requests. Hit enter to install.



## Usage:

1. Double-click the exe file "DOROCharacterSwapper.exe". If the tool asks you to Run as Admin you must to allow it.
2. You will see the message "Write the character name to be swapped:", write the character that will be swapped. For my example I write Naga. Hit Enter.
3. You will see another message "Write the skin number for [character name]:", if you want to swap a default character you must to write 00, if it's a skin you must to write the corresponding number 01/02/03/04 etc. For my example I write 00 since it's default Naga. Hit Enter.
4. You will see another message "Write the character name you will use for the swap:", write the other character that will be used for the swap. For my example I write 2B. Hit Enter.
5. You will see the message "Write the skin number for [character name]:" again, write the corresponding skin number you want. For my example I write 01 since I'm swapping 2B skin (01) over default Naga (00). Hit Enter.
6. Wait until the tool finishes to process stuff, you will see the message "Press enter to continue" three times so just hit Enter until the Terminal window continues with the process.
7. If everything worked you will see the swapped character files saved on your Desktop in a new folder named "CHARACTERS_SWAPPED".
8. Move those files from that folder "CHARACTERS_SWAPPED" to your "mods" folder located in your NMM folder.

Happy modding! ^‿^


