Moving from Window-eyes to NVDA
A very short tutorial telling you just what you need to know to do a lot of what 
you did before.
 
Author: Gene Asner

## Few words from the author

First, a word about using the tutorial.  I explain concepts in the tutorial but much of what I do is to give commands that are different in NVDA.  As I explain, a lot of what you do won't change but certain things will require different commands.
 
 To use this tutorial effectively, practicing many commands I give might be very useful.  For example, when I give screen review commands, stopping reading and practicing in this document might help you remember and learn them.  When I describe input help, turning it on and trying different keys and combinations of keys might be helpful.  You will find, for example, that the screen review commands I give are announced when you have key describer on and issue the commands.  That will help you review quickly and efficiently if you for get any of them, something 
that is far more likely to occur in the laptop layout than the desktop layout.  Now that I've suggested ways to use it effectively, the tutorial begins.
 
## Introduction

Many people are apprehensive about switching to NVDA or any other screen-reader from Window-eyes.  This tutorial will explain and demonstrate that such apprehensions are largely based on misunderstandings.

Before I discuss the misunderstanding that causes most of this apprehension, I'll briefly discuss installing NVDA and changing the synthesizer used and speech parameters.
 
## Installation

NVDA has a talking installer.  run the file as you would any installation file.  you may get a dialog asking if you want to run the file.  Use the command alt r for run.  If you get a UAC prompt, answer alt y.

Run narrator.  Then run the NVDA installer. when you run the installer, there will be a pause and then a bit of music will play.  Not long after, the talking installer will run.  Unload Narrator at that point.  return to the install dialog.

Tab through the choices.  Accept the license agreement and then tab to install. You will get other options but install is the one you want.

### About voices

Don't stop using NVDA because of the voice.  A lot of people don't try NVDA because of the voice.  As soon as you get it set up, I'll tell you how to change the synthesizer used.
 
## Welcome dialog

When NVDA is installed and running, a dialog box comes up with some explanatory text and the ability to set one or two options.  While I know a lot of people very much dislike the default voice, it's worth listening to the dialog and looking at the settings by tabbing through them.

I would recommend checking the check box to use caps lock as an NVDA modifier.  You'll see why I recommend this in later discussion.
 
## Changing synthesizers and voice settings

After you go through the initial welcome dialog, it's time to learn how to change the synthesizer.  Issue the command control insert s.  Use either insert.  From now on, assume you can use either insert unless I state differently. A synthesizer selection dialog will open.

You will see a list of different possibly available synthesizers.  Choose SAPI 5.  I know everyone has at least one SAPI 5 voice on their machine.  Up and down arrow through the list and stop on SAPI five.  Press enter. You will now hear another voice.  It may be the same voice you hear in Narrator.

Now issue the command control insert v. You are now in the voice selection and adjustment dialog. Up and down arrow to see what voices are available.  Stop on the one you want. Now tab through the dialog and change settings for the voice. Once you find a voice you want and tab through and set whatever you want such as  speed and punctuation, press the ok button.  
 
## About commands

Now, let's continue with what I spoke of at the start of this tutorial.  The misunderstanding that makes the switch to NVDA from Window-eyes or from any other screen-reader seem daunting is that the user doesn't realize that most of the commands he/she uses are Windows commands and program commands and they won't change.

Consider the following examples:

* Opening menus was and still is alt.  That's a Windows command to open menus in programs.  It's the same no matter which screen-reader you use.  
* Control o for open doesn't change.
* Using the arrow keys to move in a document doesn't change.
* Tabbing through dialogs doesn't change.  Neither does how you move 
in a list or a tree view or work with a combo box, and the list goes on.

Screen-reader commands, many of which may change, such as read title bar, provide access to information you can't get or can't get conveniently by using Windows or program commands.

for example, read title bar.  In Window-eyes, the command is control shift t.  In NVDA, it's insert t. The title bar is something a sighted person looks at.  You can't move to it with the pc cursor or application cursor, whatever you wish to call it, because there is no need.  A sighted person can just see it.  So the screen-reader has a command, read title bar.  That command is not a Windows nor a program command.

Here are the screen-reader commands you will need to know to allow you to do a lot of what you did before with Window-Eyes:

* To unload NVDA, insert q then enter.
* Read title bar, insert t.  
* Time, insert f12.  
* Announce formatting information, insert f.
* Read current Window, insert b.  In Window-eyes the command is control shift w.  
* Read to end, insert down arrow.  Use the down arrow on the main keyboard. In the laptop layout, read to end is NVDA key a.  
* Stop speech with control, as with screen-readers in general.  
 
## Screen review

I'm about to discuss screen-review commands.  those let you review the screen without changing the position of the cursor when editing a document, or changing where you are in a dialog or anywhere else.  But first, I'll point out that Commands such as left arrow, right arrow, control home, control end, control left arrow, and control right arrow are Windows movement commands for moving in any standard edit field including word processor edit fields.  None of them will change.
 
### Screen review commands

Note the pattern as I give these commands:

* Read previous line, numpad 7.  
* Read current line, numpad 8.
* Read next line, numpad nine.

You move in screen review to the previous or next line when you issue those commands.  You can keep moving and reading until you get to the top or bottom of the screen.

* Read previous word, numpad 4.
* Read current word, numpad 5.
* Read next word, numpad 6.
* Read previous character, numpad 1.
* Read current character, numpad 2.
* Read next character, numpad 3.

Note the pattern:

* Read current is the key in the middle of each of these rows.
* Move to and read previous is the key on the left.
* Move to and read next is the key to the right.

The lower the numbers, the smaller the movement unit.  1 2 and 3 move by character.  
4 5 and 6 move by word, etc.

Now, here are the laptop layout review commands:

* Read current line, NVDA shift  period
* Move to and read next line, NVDA down arrow.
* Move to and read previous line, NVDA up arrow.
* Read current word, NVDA control period
* Read previous word, NVDA control left arrow
* Read next word, NVDA control right arrow
* Announce current character, NVDA period.
* Move to and read previous character, NVDA left arrow
* Move to and read next character, NVDA right arrow.

After a little more discussion, I'll tell you how to change the keyboard layout to laptop.

Getting back to the review keys in the laptop layout, There are sort of patterns in the laptop layout but not the kind of uniform pattern as in the desktop layout. If I had a laptop computer without a numpad, I'd buy a USB numpad and not fool around with the laptop layout.  But you can decide that for yourself.  But aside from predictable keys such as that period is used for current, and that left and 
right arrows are used with modifiers, you can't generalize more.  Such patterns are not followed in every previous and next item.  In one of the previous and next items, up and down arrow is used.  

## More review commands and review modes

Here are two more important commands:

* Jump to top of window, shift numpad 7. Laptop layout command: control NVDA key home.
* Jump to bottom of window, shift numpad 9. Laptop layout command: Control NVDA key end.
 
I've said top and bottom of Window but that's oversimplified.  It depends what kind of review mode you are using.  I won't go into that to any extent in this very short tutorial.
 
### A brief introduction to review modes

If you are reviewing material in a word processor, use the review commands I've 
given. If you are in a dialog or some other structures, in order to see what is on screen, change to screen review mode. to do this, use the command numpad insert numpad 7 in the desktop layout.  In the laptop layout, the command is NVDA key page up.  Issue the command and repeat it if necessary until you hear screen review. Then you can use the review commands such as numpad 7, 8 9, etc. to review what is on screen.

After you have finished working in screen review, it is very important to return to object review.  Issue the command numpad insert numpad one in the desktop layout.  the laptop layout command is NVDA Key page down.  Repeat the command  if necessary until you hear object review.  If you don't do this, you will often hear incorrect information about where you are when you do various things in NVDA.

## Changing keyboard layout

I shall now explain how to change the layout from the desktop to the laptop layout 
and discuss causing the caps lock to be used as an NVDA key.  If you add capslock, you can still use either insert; there are times when caps lock is very convenient.
 
to open keyboard settings, issue the command control insert k. You are now in a list of layouts. the desktop is the default and the first in the list. If you want to switch to the laptop layout, down arrow once and then tab to and activate the ok button.  

As you tab, you will notice check boxes about which keys serve as the NVDA key. Caps lock is not checked.  Check it with the space bar. You can stay in the desk top layout and still tab and see these check boxes.

I use the caps lock key as an NVDA key often and I use the desktop layout.  I find it much more convenient to use for the read to end command.  I hold caps lock and press down arrow.  That is, to me, much more convenient than using insert down arrow, regardless of which insert I use.

If you want to toggle caps lock on and off for typing, press it twice quickly.  If you press it once and hold it, it serves as an NVDA key.  If you press it twice quickly, it toggles caps lock on and off.
 
## Mouse commands and review modes

To left click with the mouse, route the mouse to the review position with the command numpad insert numpad slash.  That is the same command you left click wwith in Window-eyes.  If you want to right click, route the mouse with the same command (numpad insert numpad slash), then use numpad star, the key immediately to the right of numpad slash.  In other words, you right click with the same key you use in 
Window-eyes.

Screen review, though the commands are different, is similar in concept to using the mouse pointer in Window-eyes. Object navigation is different from any review mode in Window-eyes.  I won't teach its use here but you will find a discussion of it in a tutorial I will give an address for later in this tutorial.  Depending on how you use your computer, you may find it very useful.  
 
That is just about all I will teach in this very short tutorial about screen review and mouse.  As I said, its purpose is to allow you to do much of what you do with Window-eyes quickly and easily.  But  I'll tell you a few more things.
 
## Internet browsing:

When you are on a web page, quick navigation commands are almost identical whether you are using NVDA or Window-eyes:

* Move by headings is h.
* Skip blocks of links is n.
* Move to next button is b.
* Next combo box is c.
* Next check box is x.

## Input help mode

NVDA has an input help mode which is similar to what is in Window-eyes.  Insert and 1 on the main keyboard turns it on. When you press a key or combination of keys that might be a command, you will hear what the keys are and what, if any command they execute.  This varies depending on where you are.

When in a browser that supports browse mode, typing a lot of individual letters will give you information about what the keys do in browse mode.  I already gave much of that information above but you may want to press a lot of keys using input mode in a browser. To turn input mode off use the same command you used to turn it on, insert 1.
 
## Additional information

To learn more about NVDA, a popular tutorial is available at:

http://www.josephsl.net/tutorials

On that page, you will see links to download different sections of the tutorial dealing with different subjects.  You can also download the entire tutorial as a zip file.
 
There is also an e-mail list for NVDA users.  To join, send a blank message to this 
address:

nvda+subscribe@nvda.groups.io
 
I hope that this tutorial has removed much of your apprehension about switching to NVDA.  Now, as you wish or need, you may consult the tutorial I gave a link to. NVDA is a powerful screen-reader and it will meet a lot of users needs as well as JAWS or Window-eyes does.  I hope this very short tutorial gives you a good foundation on which to build confidence that the transition should be much easier than you may have thought and that it will help make it much more enjoyable.

The End
