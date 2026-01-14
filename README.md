# Glyph
An [AutoHotkey v2](https://www.autohotkey.com/) script for typing diacritical characters (accent marks) on a QWERTY keyboard. Glyph contains all [precomposed Latin diacritic letters in Unicode](https://en.wikipedia.org/wiki/List_of_precomposed_Latin_characters_in_Unicode#Letters_with_diacritics).

![GIF showing the word "Café" being typed. For the E, CapsLock+E is pressed to open Glyph, and the acute é is selected.](https://github.com/Cordarian/Glyph/blob/main/Glyph%20demo.gif?raw=true)

## Usage
Hold the CapsLock key and any letter to bring up a list of diacritics for that character. Choose the character you want to type by double-clicking it, or select it with the arrow keys or by typing the first letter of the diacritic and pressing Enter. The first 10 characters in the list can also be inserted immediately by pressing the number keys 1-10, where 0 is 10.

## Run at Startup
To run Glyph automatically when your computer starts, place the .exe or .ahk file into the File Explorer folder located at `%appdata%\Microsoft\Windows\Start Menu\Programs\Startup`

## How does it work?
This stand-alone tool is written in AutoHotkey v2. You can download and run the .exe file by itself, or view the whole code in the .ahk file, which can be run without the .exe [using AutoHotkey](https://www.autohotkey.com/docs/v2/Tutorial.htm#s11).
