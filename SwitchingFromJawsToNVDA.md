# Switching From JAWS To NVDA

## Introduction

The purpose of this guide is to assist users of JAWS (Job Access With Speech), a commercial screen reader by Freedom Scientific to switch to the open source screen reader NVDA (NonVisual Desktop Access) with ease. It assumes prior knowledge of JAWS and that you are proficient in it's use.

It is not intended to be a replacement  of the included user guide, rather as a means to make NVDA seem less daunting.

## Strengths And Weaknesses 

The intent of this guide is not to be a comparison of JAWS and NVDA, but it is necessary to mention some things that NVDA doesn't currently support or that needs improving so you can make an informed choice.

Support for advanced features of the Microsoft office suite is a fairly recent addition, so you may not find it as polished an experience as JAWS.  However, this has been improved significantly in recent versions, and is constantly being worked on.  

With that said, you'll find that - in most daily situations, NVDA works just as well as JAWS, if not better in some cases.

## A Quick Note about NVDA's Laptop Keyboard Layout

Selecting the laptop keyboard layout does not automatically set the CapsLock key to act as the NVDA modifier key.  However, a check box is provided next to the Keyboard Layout combo box to toggle this setting.

## Note On The Insert Key.

As  you may be aware, both JAWS and NVDA can use the insert key for it's modifier key. Both screen readers treat it slightly differently, which could lead to some confusion if you are used to one or the other.

With JAWS loaded, the insert key is solely for it's use. This means that, in order to use the original function assigned to it (such as switching between insert and overwrite modes in a text editor or word processor), you first have to activate JAWS's pass key through command.

NVDA on the other hand allows you to carry out the insert key's original function by pressing it twice quickly.
Keep this in mind the next time you're editing text while using NVDA and find yourself erasing what you've already written by typing over it.

## Alternatives to eSpeak

eSpeak NG is the speech synthesizer that is included with NVDA. Like NVDA itself, it is also free and open source, which is one of the reasons for it's inclusion. Another being the shear amount of languages it can speak.

However, you may find that, for whatever reason, it is not for you. If this is the case you will be glad to know that there are alternatives, which will be discussed in the following sections.

### Eloquence

One of the most asked questions concerns the use of the Eloquence synthesizer with NVDA. Until recently, [it was illegal to do so, as explained by a developer.](http://community.nvda-project.org/blog/NVDAAndEloquenceSituation)

However, Code Factory has released [a version of eloquence as an NVDA add-on which can be purchased from this link.](http://codefactoryglobal.com/app-store/voices-for-nvda/)

A license to use Nuance's Vocalizer synthesizer is also included in the price.

See the section entitled "Scripts" for information about NVDA add-ons.

### Windows OneCore voices

If you are on Windows 10 and are running NVDA version 2017.3 or later, you have yet another alternative in the shape of Windows OneCore voices. These voices are developed by Microsoft and are included free of charge with windows 10.

There are quite a few available in various languages and dialects; some of which will already be installed. However, these will vary depending on the language packs you have on your system. The only way at present to get new voices is to install other language packs in Settings. Once done, you can then download the voices for that language. At which point, you can remove the language pack. This will not effect the voices you have just installed.
hopefully this will be made more simpler in the future.

If you find that Windows OneCore voices do not speak fast enough, even when NVDA's speech rate is at it's highest, adjust the speech rate in windows settings as well.

Their slight complications aside, these voices offer a viable alternative to eSpeak NG as they are responsive and quite natural sounding.

### Even more voices

If you still cannot find the perfect voice for you, [This page lists several other speech synthesizers (both free and paid you can use instead.](http://community.nvda-project.org/wiki/ExtraVoices)

## Terminology

Most of the time, both NVDA and JAWS share a lot of the same terminology to describe controls e.g. radio buttons, combo boxes, check boxes etc.

One notable difference is that NVDA differentiates between single and multi-line edit fields, and will also tell you if a field is "protected" (anything you type will be replaced by asterisks).  It will also alert you if text is selected in a field when you tab over to it.  If so, typing will replace the highlighted text.

NVDA  refers to the different languages a speech synthesizer can speak as voices, and the different voices  supported by your synthesizer as variants.

## Cursors

NVDA has various cursors to aid in navigating Windows and applications, similar to JAWS.  The terminology is slightly different as described below.

The PC cursor in NVDA's documentation is referred to as the system focus and system caret.

The equivalent to the JAWS cursor is a combination of object navigation, the review cursor and the various review modes; such as  Document review, object review and Screen Review. The Screen Review function is the one perhaps most similar to the JAWS cursor, however it is beneficial to become familiar with all of these. You will find thorough, easy to understand instructions in the user guide.

Unlike JAWS, you don't have to switch between the PC and JAWS cursor equivalents as the numpad is reserved exclusively for working with the JAWS cursor like functions.

It is worth noting that when you use object navigation or the review cursor, the mouse does not move in sync. You have to press a command to move the mouse to the location of the review cursor, which is similar to how JAWS' "invisible cursor" works. There are also commands to simulate clicking or locking both mouse buttons.

However, if you simply want to activate the current object you are focused on when using object navigation, there is a command to do this without having to move the mouse cursor to it first.

### Touch cursor

In JAWS 15 or later, you can use numpad keys to navigate apps using a tree-like structure, similar to how users of smartphone screen readers such as VoiceOver would navigate touchscreens. in NVDA, object navigation and object mode touch commands can be used for this purpose

## Virtual Cursor

The virtual cursor in NVDA is known as browse mode. It functions in much the same way as JAWS, giving you access to navigation quick keys, or in NVDA speak, single letter navigation.

Following are some common issues you may encounter when browsing the web with NVDA for the first time, and how to address them.

### Why Is Everything On One Line?

In case you are unaware, JAWS has two modes for displaying webpages or other documents using the virtual cursor; simple layout and screen layout.  Simple layout is the default, which displays content in a linear fashion - putting each link or control on its own line.  Screen layout formats the content similar to how it's displayed on screen.

The default in NVDA is screen layout, but you can easily switch to its version of simple layout by pressing NVDA+V while in browse mode. This will turn Screen layout off. Be sure to save your configuration after making this change with NVDA+CTRL+c.

### It Keeps Saying Clickable Clickable Clickable.

While  reading webpages, you might notice sometimes that NVDA says "clickable", even multiple times on the same link or control.

However, this is easily fixable as of version 2014.1 or later. Go to the Document Formatting dialogue, uncheck the "Report if clickable" check box and press OK. Remember to save your configuration.

### Find doesn't work on the web.

While JAWS is loaded, pressing ctrl+f in Internet Explorer or Firefox brings up the JAWS Find dialogue rather than activating the browser's built-in find command.  This is to allow you to search for text using the virtual cursor.  The regular find command will search for the next occurrence of the entered text, but will not move the virtual cursor to that location.  This is due to how screen readers interact with web pages.

NVDA has its own find command to search in browse mode, but it has not been tied to CTRL+F, so pressing that shortcut key calls up the browser's find command, hence find not working as expected.

To bring up NVDA's find dialogue, press ctrl+NVDA+F.  Type in what you wish to find then press enter.

### No commands to view forms and headings?

In JAWS, you can press JAWS+F5 to list forms, JAWS+F6 to list headings and JAWS+F7 to list links. In NVDA, the latter two have been combined into an elements list dialog, and you can access it by pressing NVDA+F7.

## Forms Mode

The equivalent of forms mode in NVDA is focus mode, and it behaves very similar to JAWS, Even switching modes automatically when navigating through a webpage. It will play a sound alerting you to which mode you are in.

Details about Focus Mode can be found in the user guide.

## NVDA talks too much.

Sometimes you may find that NVDA can seem overly verbose, particularly in some list views. This is because as far as NVDA is concerned, list views are tables.   NVDA is configured by default to announce each column or row header.

To turn that option off, uncheck "Report table row/column headers" in the "Document Formatting" dialogue.

## Solving unexpected Speech Dictionary behaviour.

NVDA has always included a function to edit "Speech Dictionaries", which are similar to JAWS' dictionary manager files.  However, until recently, the result of adding a word to them might not be what you had expected.
If you added a word you wanted to change the pronunciation of to a dictionary , such as "mono", any word that started with or included the word mono would be affected.  Whereas in JAWS, only the text entered into the "actual word" field would be affected, unless you appended an asterisk (*). So as in this example, mono would be seen as a route word.

There was a work around, but this involved regular expressions, which aren't at all obvious to the average user.  However, as of 2014.4 or later, you will now find a group of radio buttons in the Add/edit dictionary entry labelled type, which determines how the text in the pattern, (NVDA speak for actual word), box will be treated.
 * anywhere, which is the default behavior.
 * Whole word, which is how JAWS handles dictionary entries.
 * Regular Expression, which is complicated.
You will also find a case sensitive check box.

If you previously found NVDA's speech dictionaries frustrating, be sure to take another look.

## Scripts

Like JAWS, scripts can be added to NVDA to provide support  for other applications or to add new features that can be accessed from anywhere.  These script packages are called NVDA Add-ons.  You can find several add-ons here:
http://addons.nvda-project.org/.

These include a few that emulate JAWS features not currently present in NVDA such as a system tray list, virtualise window function and ability to append text to clipboard. Scripts for popular applications such as GoldWave are also available. The user guide has details on installing add-ons, and you can read help documentation that comes with each add-on to learn more about how to use the add-on.

The following link is to the developer guide with information on how to create ad-ons. http://community.nvda-project.org/documentation/developerGuide.html

## Remote access

In 2015, Christopher Toth and Tyler Spivey released a free add-on to allow NVDA users to provide remote support, similar to JAWS Tandem. To learn more about this add-on, go to http://www.nvdaremote.com.

## Application-specific settings

Until recently, NVDA's settings were global (applied everywhere). Starting with NVDA 2013.3, it is possible to configure certain settings to be applied when using a program. This is done by creating an app-specific configuration profile. To create an app-specific profile, open the Configuration Profiles dialogue while using the app in question. To open the dialogue, hit NVDA, N, to bring up the NVDA menu. arrow down until you hear configuration profiles.  

When the dialogue opens, select New, and select "current application" when asked when to use this profile.

### Alternate say all

In recent versions of JAWS, you can configure a different speech synthesizer to be used when say all is active. You can do this in NVDA by creating a say all profile in the configuration profiles menu.

Here are the steps.

1. Open the configurations profile from the main NVDA menu. Press NVDA, N, then arrow down to configuration profiles.
2. Create a new profile by tabbing to the *new* button or press alt, N.
3. After you name your profile, tab to the profile usage radio butttons. arrow down untill you hear say all. Hit *OK* 

while  this profile is active, you need to complete the process by configuring the synthesizer while the say all profile is active.
