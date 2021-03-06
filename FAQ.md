# Frequently Asked Questions

This article answers frequently asked questions about NVDA. If you have questions or issues regarding support for specific applications, please see ApplicationSupport. If you are having problems with NVDA, please see [wiki:Troubleshooting]. For information on contributing to NvDA, including translations, see [development].

----
[[PageOutline(2-3,,inline)]]
----

## Launching NVDA

### How do I tell NVDA to start automatically when Windows starts?
1. Press NVDA+n to bring up the NVDA menu.
2. Open the preferences submenu and press enter on the general Settings.
3. Activate the Automatically start NVDA after I log on to Windows checkbox, then press enter.

NVDA will now start after you log on.

### How do I make NVDA start at the Windows Logon screen?
1. Press NVDA+n to bring up the NVDA menu.
2. Open the preferences submenu and press enter on the general Settings.
3. activate the Use NVDA on the Windows logon screen checkbox, then press enter.

### How do I make NVDA start automatically from a USB drive when it is connected?
Please see [wiki:RunningAutomaticallyFromAUSBDrive].

## NVDA GETTING STARTED

### Is there a Getting Started guide to NVDA?
Yes there is a Getting Started Guide attached to this page which is an edited version of parts of the user guide and is meant for new users.

### Are there additional tutorials for new NVDA users?
Yes. Some users produced text and audio tutorials for new NVDA users.

[NV Access has a shop with paid training materials](https://www.nvaccess.org/shop/) and services, including phone support.

Accessibility Central has [a wide array of free text and audio tutorials for NVDA.](http://accessibilitycentral.net/nvda%20tutorials%20for%20other%20programs.html)

The American Foundation for the blind offers a video tutorial series that talks about using NVDA and Google Drive. These are fully narrated videos with text transcripts and activities and can be downloaded in Mp3 format as well.

## Windows versions and features

### Which version of Windows does NVDA support?

NVDA supports the following Windows operating systems:
* Windows XP Home/Professional/Media Center.
* Windows Vista (all editions).
* Windows 7 (all editions).
* Windows 8 and 8.1 (all editions except RT).
* Windows 10 (all editions except S and Mobile).
* Windows Server 2003/2008/2008 R2/2012/2012 R2/2016.

### Does NVDA support 64-bit Windows?
Yes. NVDA supports both 32-bit and 64-bit editions of Windows.

### I want to use a touchscreen. Does NVDA support touchscreens?
Yes. If you have NVDA 2012.3 or later installed on a Windows 8 PC with touchscreen, you can use touchscreen commands with NVDA. Note that this is a basic and experimental support.

## Supported synthesizers and braille displays

### What synthesizers does NVDA support?
Besides eSpeak, NVDA supports the following synthesizers:
* Microsoft SAPI 4, SAPI 5 and Speech Platform.
* Newfon.
* Nuance Vocalizer for NvDA (driver versions 2 (Vocalizer Automotive) and 3 (Vocalizer Expressive); require purchase of license).
* And many others.

### What braille displays does NvDA support?
NvDA supports the following braille displays (some models allows computer braille entry):
* Alva BC640/680.
* Handy Tech models (Braille Wave, Braillino, etc.).
* Freedom Scientific PAC Mate portable displays, Focus 40/80 USB and 14/40/80 Blue.
* Baum Vario, Pocket Vario, Super Vario and others.
* APH Refreshabraille 18.
* HumanWare BrailleNote, Brailliant (older and Bi/B series), Braille Connect.
* Papenmeier Braillex EL USB and serial displays (2D Screen, Trio, etc.).
* Seika versions 3, 4, 5 and Seika 80.
* HIMS Braille Sense, Braille Edge, SyncBraille.
* Hedo braille displays.
* And many others via BRLTTY.

For more information on NVDA and braille displays, refer to the user guide.

Some braille display manufacturers such as Eurobraille built their own braille driver as an addon for NVDA. Please ask your manufacturer if he isn't listed here.

## Running NVDA

### What is the difference between installed, portable and temporary versions of NVDA?
The installed version has no restrictions - can use a touchscreen, can be used on secure screens such as User Account Control( UAC) and can be used during logon. Portable version is useful for using on a USB flash drive. Temporary (or installer) version is useful for demonstration purposes or burning to a CD.

Please see the userguide for more informations.

### Does NVDA provide its own tips for using a program?
Not at this point. It is recommended that you read the manual for the program in question to find out tips for the program.

## NvDA features and terms

### What is the difference between focus and navigator object?
Focus refers to controls which can be navigated using the keyboard, such as edit fields, buttons, documents and so on. The navigator object is the object you are interested in, such as the focused control, status bar and so on. By default, the navigator object is located on the focused control, but you can detach the navigator object to explore different parts of the screen such as toolbars, status bars and controls in other programs. Once detached, navigator objects can be routed to focused control and vice versa.

### Is there something equivalent to JAWS cursor and other mouse commands in NVDA?
Yes. The screen review allows reading the contents of the current window. To switch to screen review, press NvDA+Numpad 7. Once you locate the position where you wish to perform mouse clicks, route the mouse by pressing NvDA+Numpad slash, then press Numpad slash for left mouse click or Numpad star for right mouse click. To switch to object review, press NVDA+Numpad 1.

