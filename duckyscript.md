#DuckyScript
Ducky Script is the language of the USB Rubber Ducky. Writing scripts for can be done from any common ascii text editor such as Notepad, vi, emacs, nano, gedit, kedit, TextEdit, etc.

##Syntax
Ducky Script syntax is simple. Each command resides on a new line and may have options follow. Commands are written in ALL CAPS, because ducks are loud and like to quack with pride. Most commands invoke keystrokes, key-combos or strings of text, while some offer delays or pauses. Below is a list of commands and their function, followed by some example usage.

In the tables below //n// represents a number and //Char// represents characters A-Z, a-z.

##REM
Similar to the REM command in Basic and other languages, lines beginning with REM will not be processed. REM is a comment.

```
REM The next three lines execute a command prompt in Windows
GUI r
STRING cmd
ENTER
```
##DEFAULT_DELAY or DEFAULTDELAY
DEFAULT_DELAY or DEFAULTDELAY is used to define how long (in milliseconds * 10) to wait between each subsequent command. DEFAULT_DELAY must be issued at the beginning of the ducky script and is optional. Not specifying the DEFAULT_DELAY will result in faster execution of ducky scripts. This command is mostly useful when debugging.```

```
DEFAULT_DELAY 10 
REM delays 100ms between each subsequent command sequence
```

##DELAY
DELAY creates a momentary pause in the ducky script. It is quite handy for creating a moment of pause between sequential commands that may take the target computer some time to process. DELAY time is specified in milliseconds from 1 to 10000. Multiple DELAY commands can be used to create longer delays.

```
DELAY 50
REM will wait 500ms before continuing to the next command.
```


##STRING
STRING processes the text following taking special care to auto-shift. STRING can accept a single or multiple characters.

STRING | a...z A...Z 0...9 !...) `~+=_-"';:<,>.?[{]}/\|!@#$%^&*()

```
GUI r
DELAY 50
STRING notepad.exe
ENTER
DELAY 100
STRING Hello World!
```


##WINDOWS or GUI
Emulates the Windows-Key, sometimes referred to as the Super-key.

```
GUI r
REM will hold the Windows-key and press r, on windows systems resulting in the Run menu.
```


##MENU or APP
Emulates the App key, sometimes referred to as the menu key or context menu key. On Windows systems this is similar to the SHIFT F10 key combo, producing the menu similar to a right-click.

```
GUI d
MENU
STRING v
STRING d
REM Switch to desktop, pull up context menu and choose actions v, then d toggles displaying Windows desktop icons
```

##SHIFT
Unlike CAPSLOCK, cruise control for cool, the SHIFT command can be used when navigating fields to select text, among other functions.

SHIFT | DELETE, HOME, INSERT, PAGEUP, PAGEDOWN, WINDOWS, GUI, UPARROW, DOWNARROW, LEFTARROW, RIGHTARROW, TAB

```
SHIFT INSERT
REM this is paste for most operating systems
```


##ALT
Found to the left of the space key on most keyboards, the ALT key is instrumental in many automation operations. ALT is envious of CONTROL

ALT |END, ESC, ESCAPE, F1…F12, Single Char, SPACE, TAB

```
GUI r
DELAY 50
STRING notepad.exe
ENTER
DELAY 100
STRING Hello World
ALT f
STRING s
REM alt-f pulls up the File menu and s saves. This two keystroke combo is why ALT is jealous of CONTROL's leetness and CTRL+S
```

##CONTROL or CTRL
The king of key-combos, CONTROL is all mighty.

CONTROL | BREAK, PAUSE, F1…F12, ESCAPE, ESC, Single Char | | CTRL | BREAK, PAUSE, F1…F12, ESCAPE, ESC, Single Char

```
CONTROL ESCAPE
REM this is equivalent to the GUI key in Windows
```


##Arrow Keys
DOWNARROW or DOWN | | LEFTARROW or LEFT | | RIGHTARROW or RIGHT | | UPARROW or UP


##Extended Commands
These extended keys are useful for various shortcuts and operating system specific functions and include:

```
BREAK or PAUSE
CAPSLOCK
DELETE
END
ESC or ESCAPE
HOME
INSERT
NUMLOCK
PAGEUP
PAGEDOWN
PRINTSCREEN
SCROLLOCK
SPACE
TAB
```