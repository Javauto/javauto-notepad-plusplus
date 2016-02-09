![alt tag](https://cloud.githubusercontent.com/assets/3797402/12898899/c04d2f5c-ce8d-11e5-96ad-0d35c37a9f9a.png)

## Javauto Notepad++ 

Syntax highlighting and auto completion for [Javauto](http://javauto.org/) files in [Notepad++](https://notepad-plus-plus.org/) 

![notepad](http://htejera.ukelelestudio.com/adbutil/images/notepad.png)

The color scheme is built for the default theme (white background).

## Description

There are 2 Notepad++ add-on features in this repository:

* An XML file that gives you syntax highlighting/coloring for **.javauto** files and brings you ability to fold code structure. [userDefineLang_Javauto.xml](https://github.com/Javauto/javautoNotepad-plusplus/blob/master/userDefineLang_Javauto.xml)

* An XML file to make Notepad++ able to detect Javauto functions. [javauto.xml](https://github.com/Javauto/javautoNotepad-plusplus/blob/master/javauto.xml) 


## Install

### Syntax highlighting
* Make sure you have Notepad++ installed with the option to use %APPDATA% (which is the default).
* Download the [userDefineLang_Javauto.xml](https://github.com/Javauto/javautoNotepad-plusplus/blob/master/userDefineLang_Javauto.xml) FILE
* Start Notepad++ and open the "Define your language..." (Under the "Language" tab)
* Click "import" and select the **userDefineLang_Javauto.xml** file.
* Restart Notepad++
* Open **.javauto** file and you should now have syntax highlighting.

## Auto completion 
* Download the [javauto.xml](https://github.com/Javauto/javautoNotepad-plusplus/blob/master/javauto.xml)  file
* Close all instances of Notepad++
* The AutoComplete files are located in the **plugins\APIs** folder, to be found in the Notepad++ Install Folder, most often **C:\Program Files\Notepad++**. Copy the **javauto.xml** file into this folder.
* Restart Notepad++
   

#License

Javauto is licensed under the terms of the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)


 

