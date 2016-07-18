# Winkel Core
An Arduino Core for the Winkel Boards

## Description
There are two versions of Winkel Boards [Winkel Mini](#) and [Winkel Mega](#). 

Winkel Core is an Arduino core the Winkel boards, specifically for Winkel Mini.

Because Winkel Mini has ATmega128 at its core which is not supported by default by Arduino IDE. A custom bootloader for ATmega128 was needed to provide support for widely used Arduino IDE. A special thanks to MCUdude who wrote an [Arduino Core for ATmega128 and ATmega64](https://github.com/MCUdude/MegaCore) all running a modified version of Optiboot known as **MegaCore.**

Winkel Core is just a modified version of MegaCore to suit Winkil Mini's purposes. You can perform a [Boards Manager Installation](#) or go for a [manual installation](#) so that "Winkel Mini" apperas as a board under "Tools"->"Boards"



