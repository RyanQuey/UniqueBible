# Looking for Android / iPhone / iPad versions?

We have recently launched our mobile versions in Google Play Store and Apple App Store.

Illustrated User Manual: <a href='https://www.uniquebible.app/mobile'>https://www.uniquebible.app/mobile</a><br>
Links for downloads: <a href='https://www.uniquebible.app/download'>https://www.uniquebible.app/download</a>

Description below is about desktop version, running in Windows / macOS / Linux / Chrome OS

# UniqueBible
A cross-platform & offline bible application, integrated with high-quality resources and unique features.

<b>Tested in:</b> Windows, macOS and Linux (Ubuntu & Mint)

(developed with Python [version: 3.7.2])

Visit <a href="https://BibleTools.app" target="_blank">https://BibleTools.app</a> for further information.

# Screenshot:

<img src="screenshots/screenshot.png">

# Pre-requisite

Install a Pyhton Distribution First!

The "desktop" version of "UniqueBible.app" is programmed with python library.  Users have to install python library first in order to run "UniqueBible.app" on your desktop OS.

Go to <a href="https://www.python.org">https://www.python.org</a> for instructions on installation of python for FREE.

We also recommend <a href='https://www.anaconda.com/'>Anaconda python distribution</a>.  It may be easier to be installed.

# Install Dependencies

> pip3 install PySide2
<br>(PySide2 is required for graphical user interface, used by UniqueBible.app.)

> pip3 install PyPDF2
<br>(PyPDF2 is required for reading text from *.pdf documents.)

> pip3 install python-docx
<br>(python-docx is required for reading text from *.docx documents.)

> pip3 install gdown
<br>(gdown is required for downloading database files from google drive.)

> pip3 install diff-match-patch
<br>(it is an essential component for advanced verse comparison <b>from version 5.7 onwards</b>.)

If you use use <a href='https://www.anaconda.com/'>Anaconda python distribution</a>, use the following commands instead to install dependencies [<a href="https://github.com/eliranwong/UniqueBible/blob/master/installation/mac.md">Click here for an example of installation using Anaconda</a>]:

conda install -c conda-forge pyside2<br>
conda install -c vladsaveliev gdown<br>
conda install -c conda-forge pypdf2<br>
conda install -c conda-forge python-docx<br>
conda install -c conda-forge diff-match-patch

# Instructions on Installation

There are different ways to setup and run our app.  We have some examples in the following link:

https://github.com/eliranwong/UniqueBible/blob/master/installation/Readme.md

# Graphical User Interface

A guide on GUI:

https://github.com/eliranwong/UniqueBible/wiki/graphical_user_interface

# Supported Commands

UniqueBible.app supports a set of command lines for quick navigation to bible passages or tools.

<img src="screenshots/screenshot_command_line.png">

For details, read:

https://github.com/eliranwong/UniqueBible/wiki/command_line

# Where are the Database Files?

All codes for running the app is shared in this repository.

Github has restrictions on upload size.  For this reason, full set of database files is not able to be uploaded here.

To run UniqueBible.app and its features, several database files are required.  To help you about installing particular datasets, <b>"Download Helper"</b> comes up automatically, when a database file is needed for a particular feature.

You can also manually install <b>"ALL"</b> https://marvel.bible datasets via our menu bar.<br>
Go to "Resources" > "Install Marvel.bible Datasets"

<i><b>Remarks:</b></i> It takes time for large files to be downloaded.  The core datasets for running UniqueBible.app is 49MB in size.  You may need to wait for a while for downloading it after you first launched UniqueBible.app.

# 3rd Party Resources

In ADDITION to official UniqueBible.app data, you can convert resources from third-party modules and import into UniqueBible.app.

Currently, we support conversion and import of modules of <b>MyBible</b>, <b>e-Sword</b>, <b>MySword</b>.

For more information, read:

https://github.com/eliranwong/UniqueBible/wiki/third_party_resources

# Customise Configurations [optional]

Read: https://github.com/eliranwong/UniqueBible/wiki/config_file

# Change Default Font [optional]

Read the following example:

https://github.com/eliranwong/wsl2/blob/master/bible_apps/desktop.md#change-default-font

# Customise the location of "marvelData" [optional]

Read this example: https://github.com/eliranwong/UniqueBible/blob/master/installation/windows_wsl2.md#shared-marveldata-folder-in-windows-drive-c-optional

# Virtual Keyboards [optional]

Virtual Keyboard is NOT turned on by default.  You can enable it according to your needs.

For more information, read: https://github.com/eliranwong/Chrome-OS-Linux/blob/master/unique-bible-app/desktop.md#use-virtual-keyboard

<img src="screenshots/screenshot_virtualKeyboard.png">

<b>Remarks:</b> You need to close the virtual keyboard before you can close the app.  You can use the button located at the right lower corner of the virtual keyboard to close it.

# Donations:

Please consider a donation via our PayPal account:
<a href="https://www.paypal.me/MarvelBible">https://www.paypal.me/MarvelBible</a>

