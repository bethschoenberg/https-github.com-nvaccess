# Application Support

This article provides information about NVDA's support for specific applications, including answers to common questions, tips and potential issues. Unless otherwise specified, information on this page refers to the latest stable version of NVDA.

----
[[PageOutline(2-3,,inline)]]
----

## [Mozilla Firefox](http://www.getfirefox.com/) (recommended web browser)
Mozilla Firefox provides secure and accessible web browsing experience. [http://www.mozilla.com/en-US/firefox/all-older.html Although some older versions are supported by NVDA the latest stable version is strongly recommended.

## [Mozilla Thunderbird](http://www.getthunderbird.com/) (recommended email client)
Mozilla Thunderbird provides the best overall email experience with NVDA. [Latest stable version](http://www.mozilla.org/en-US/thunderbird/all-older.html) is recommended.

## [Adobe Flash Player](http://www.adobe.com/products/flashplayer/)
NVDA supports accessible Flash content on the web. The latest version of Flash Player is recommended.

Even if you aren't using Internet Explorer, you must install the Internet Explorer version of Flash Player as well.

## [Microsoft Internet Explorer](http://windows.microsoft.com/en-US/internet-explorer/products/ie/home)
NVDA supports Microsoft Internet Explorer. The latest version is recommended. The minimum supported version is 6. Accessibility has improved in more recent versions of Internet Explorer.

## [Microsoft Office](http://office.microsoft.com/) (recommended office suite
NVDA provides excellent support for Microsoft Word, Excel and Outlook, which are part of Microsoft Office. PowerPoint is currently supported, although this support is somewhat basic. Access is not yet supported. The minimum supported version is 2003, and it is recommended to use Office 2007 or later.

### How can I navigate complex documents in Word or read HTML messages in Outlook?

In NVDA 2015.1, you can use browse mode to read Word documents containing links, headings and so on, as well as navigate through HTML messages in Outlook. Browse mode is supported in Word and Outlook 2007 or later.

To use browse mode in Word or Outlook, once a document or an HTML message is opened, press NVDA+SPACE. In Word, to edit the document you are reading, press NVDA+SPACE to switch to focus mode.

## [Skype](http://www.skype.com/)
Skype works quite well with NVDA. The latest version (7.0) is recommended.

## [Apache OpenOffice](http://www.openoffice.org/)
!Apache OpenOffice is an alternative office suite to Microsoft Office and is reasonably accessible. Currently, OpenOffice provides same level of access as IBM Lotus Symphony. Minimum supported version is 4.1.

!However, if you need to use older versions, follow this steps:
!Once OpenOffice.org is installed, you will need to:
 * Download and install [Java](http://www.java.com/).
 * Download and install the [Java Access Bridge](http://java.sun.com/javase/technologies/accessibility/accessbridge/).
  * Java Access Bridge is included with Java SE Runtime Environment (JRE) Release 7 Update 6 (7u6) and later, see [this](http://docs.oracle.com/javase/7/docs/technotes/guides/access/enable_and_test.html) page for more information.
 * Enable assistive technology support in OpenOffice.org.
  * You can do this from the Accessibility page of the Options dialog. Unfortunately, before you enable this, OpenOffice is inaccessible, which makes this task extremely difficult for a screen reader user.
  * Alternatively, download and run [/3rdParty/OpenOffice_EnableAssistiveTechnologySupport.reg this registry patch].

### I can't read the OpenOffice help or other read-only documents.
To enable accessibility of read-only documents:
 1. From the Tools menu, select Options.
 2. Select Accessibility in the list of pages.
 3. Move to the "Use text selection cursor in read-only text documents" checkbox and check it.
 4. Press the OK button.