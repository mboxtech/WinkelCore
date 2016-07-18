# Winkel Core
An Arduino Core for the Winkel Boards

## Description
There are two versions of Winkel Boards [Winkel Mini](#) and [Winkel Mega](#). 

Winkel Core is an Arduino core the Winkel boards, specifically for Winkel Mini.

Because Winkel Mini has ATmega128 at its core which is not supported by default by Arduino IDE. A custom bootloader for ATmega128 was needed to provide support for widely used Arduino IDE. A special thanks to MCUdude who wrote an [Arduino Core for ATmega128 and ATmega64](https://github.com/MCUdude/MegaCore) all running a modified version of Optiboot known as **MegaCore.**

Winkel Core is just a modified version of MegaCore to suit Winkel Mini's purposes. You can perform a [Boards Manager Installation](#boards-manager-installation) or go for a [manual installation](#manual-installation) so that "Winkel Mini" apperas as a board under "Tools"->"Boards"

This core is only needed for Winkel Mini because of its ATmega128 core. The Mega version uses ATmega2560 for which there is official support by Arduino.

Please view the original repository for more details. All our releases will be in sync with the orginal releases by MCUdude but you may also choose to use the MegaCore instead of WinkelCore.

### Boards Manager Installation

This installation method requires Arduino IDE version 1.6.4 or greater.

* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**: 

`https://raw.githubusercontent.com/mboxtech/WinkelCore/master/package_WinkelCore_index.json`

* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **WinkelCore** entry and click on it.
  * **Note**: If you are using Arduino IDE 1.6.6 then you may need to close **Boards Manager** and then reopen it before the **WinkelCore** entry will appear.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.
* Go to **Tools > Board >** and you should see **Winkel Mini**

### Manual Installation
Click on the "Download ZIP" button in the upper right corner. Exctract the ZIP file, and move the extracted folder to the location "**~/Documents/Arduino/hardware**". Create the "hardware" folder if it doesn't exist.
Open Arduino IDE, and a new category in the boards menu called "WinkelCore" will show up.
