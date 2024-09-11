# Twizo

*Twizo* is a ready-to-use version of *Zotero*, specifically made for usage by students & employees of the *University of Twente*. It is based on the portable version of *Zotero*: this means users can install and update *Twizo* by downloading & running the launcher, and select a location for the app. Twizo will work regardless of other settings. It's even possible to install *Twizo* on a USB-stick to make it even more portable!

Twizo is currently only available for Windows (7 and later). We are looking into making versions available for macOS and/or Linux. 

Twizo was made & developed by [Samuel Mok, information specialist @ university of twente](s.mok@utwente.nl). 

Install
------------
- Download the latest [release](link-to-come).  
- Unpack Twizo by launching the installer to extract Twizo to a target folder (it can be an USB Key, your desktop, anywhere else...)
- Run Twizo by going to the selected folder and opening Twizo.exe
- Proceed with the initial setup as outlined in the next section below.
  
> [!TIP]
> Is the screen below preventing you from installing Twizo?
> ![image](https://github.com/user-attachments/assets/f64cf75b-ca12-415c-ae26-d92ecf9ec72b)
> Then right-click the file you just downloaded (e.g. twizo-launcher-0.3.exe in your Downloads folder) and select 'Properties'.
> At the bottom of the screen, find the 'Unblock' option, and click it so it's checked ✅:
> ![image](https://github.com/user-attachments/assets/acde229b-ac81-44c7-8a7b-78c56be28a52)
> You can now run the launcher and proceed.


Initial Setup
------------------
While Twizo aims to provide a plug-and-play solution, there are a few things the user will need to set up themselves when running Twizo for the first time.

1. Connect to your browser
2. Connect to your word processor
3. Set up metadata cloud syncing
4. Set up files cloud syncing

### 1. Connect your browser to Twizo
The browser connector lets you add items to your library straight from the web, including metadata and PDFs. This is the main way to add items to Twizo, and an essential part of using Twizo efficiently. 
Download the [Zotero Connector from the download page on zotero.org](https://www.zotero.org/download/) to get the most recent link for your browser. 
If you'd like a direct link, here they are for the most popular browsers (last update: 11 sept 2024): 
- [Chrome](https://chrome.google.com/webstore/detail/ekhagklcjbdpajgpjgmbionohlpdbjgc)
- [Firefox](https://www.zotero.org/download/connector/dl?browser=firefox&version=5.0.144)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/nmhdhpibnnopknkmonacoephklnflpho).

Note that the connector only works when Zotero is currently running.

### 2. Connect your word processor to Twizo
No matter what you use to write, there is always a method to integrate Twizo with your prefered software to enable easy & correct citations. 

#### 2.a Integration with Word and/or LibreOffice
When you install Twizo and run it for the first time, it will automatically install the connector for Word & LibreOffice, if any of them are installed on your system. You should see a new *Zotero* tab in Word if this is successful:
![image](https://github.com/user-attachments/assets/150affb6-32f7-48ad-a2f9-511d7f3ec969)

If you do not see the Zotero tab in word, try reinstalling by first closing Word, then open the Settings menu in Twizo (Edit -> Settings while having Twizo open) and 1. go to Cite, 2. scroll down to Word Processors and click Install Microsoft Word Add-in.
![image](https://github.com/user-attachments/assets/3ce105f5-b3c0-47a5-a41f-57ef41ad7090)

#### 2.b Integration with Overleaf
There are multiple ways to connect Twizo/Zotero with Overleaf. Twizo comes pre-installed with the Better BibTeX plugin which enables some additional options. The instructions below describe the recommended way to connect Twizo with Overleaf. Other methods are linked below, should you prefer a different route. 

> [!CAUTION]
> Instructions and links to come

#### 2.c Integration with Google Docs
This is easy: just install the browser connector (see 1.): this also includes the Google Docs connector. 

#### 2.d Integration with other writing software
There are many more possibilities and we can't cover them all, but if you use something else to write with you're probably used to figure things out yourself. Here are some links that might get you on the right track:
[Connect using Better BibTeX](https://retorque.re/zotero-better-bibtex/citing/cayw/): explicit links for vim, emacs, vscode, markdown, greasemonkey... but also generic guides on using [api calls / curl / etc](https://retorque.re/zotero-better-bibtex/exporting/pull/index.html) for your own applications
[VSCode plugin](https://marketplace.visualstudio.com/items?itemName=mblode.zotero)
[Obsidian plugin](https://github.com/mgmeyers/obsidian-zotero-integration)

### Metadata cloud syncing
use zotero account

### Files cloud syncing
setup filesynced folder, update settings

Update
---------
To update Twizo, just repeat the installation steps, selecting the same target folder. This should keep all of your settings and modifications -- but we recommend creating a backup of your Twizo folder first, just in case. 
> [!CAUTION]
> Do not use the built-in update function (Zotero -> Help -> Check for Updates), as this will replace Twizo and ZoteroPortable modifications with the original Zotero application. 


Modifying Twizo
--------------
You can use the various setting menus in Twizo to change how things work. See the **manual (link to come)** for more details. If you want to modify things that aren't found in the settings, you will need to dive into the configuration files. This is also how all modifications were done to make Twizo from the ZoteroPortable base. A detailed overview of changes & which files to modify can be found in the **advanced guide (link to come)**. 

Any further modifications fall outside of the scope of Twizo: then I'd suggest starting from the [ZoteroPortable repo](https://github.com/pedrom34/ZoteroPortable-dev-repo/) or the [main Zotero repo](https://github.com/zotero/zotero).

Twizo's lineage
---------------------------------------------------------------------------
This repo is a fork of [Zotero in PortableApps.com Format](https://github.com/pedrom34/ZoteroPortable-dev-repo/).
For the original version, download ZoteroPortable from [PortableApps™](https://portableapps.com/apps/office/zotero-portable). This repo contains a version that includes certain settings, plugins, and styling options specific for the University of Twente. 

This version of Zotero is not officially endorsed by Zotero Team. [Do not expect official support for portable Zotero issues](https://forums.zotero.org/discussion/64050/5-0-portable-zotero). For official changelog of Zotero, please see [Zotero's changelog](https://www.zotero.org/support/changelog).  
Similarly, any modifications made in Twizo compared to the original [Zotero in PortableApps.com Format](https://github.com/pedrom34/ZoteroPortable-dev-repo/) are not the responsibility of the author of the base version ([pedrom32](https://github.com/pedrom34)).

