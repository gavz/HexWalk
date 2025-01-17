![hexwalk](hexwalk/images/hexwalk64.png)
# HexWalk - Hex Editor/Viewer/Analyzer
 
HexWalk is an Hex editor, viewer, analyzer.

Based on opensource projects like qhexedit2,binwalk and QT.

It is cross platform and has plenty of features:

* Advanced Find (can find patterns in binary files based on HEX,UTF8,UTF16 and regex)
* Binwalk integration
* Entropy Analysis
* Hash Calculator
* Bin/Dec/Hex Converter
* Hex file editing


## Screenshots

* Main page
![hexwalk gui](screenshots/hexwalk_gui1.png)

* Advanced Search
![hexwalk gui](screenshots/hexwalk_gui5.png)

* Entropy Calculator
![hexwalk gui](screenshots/hexwalk_gui2.png)

* Binary Analyzer
![hexwalk gui](screenshots/hexwalk_gui3.png)

* Hash Calculator
![hexwalk gui](screenshots/hexwalk_gui4.png)

## Dependencies

HexWalk release executables are statically linked, so are self-contained, you can use as-is.
Binwalk functionalities need Binwalk to be installed on the OS. For Linux OS simply install binwalk with your
package manager (eg. sudo apt install binwalk)

For Windows, Binwalk support is experimental, it is done using a python helper file that launches the commands and must be on the same path of hexwalk.exe.
in order for binwalk support to work on Windows it is necessary to install Python and to install binwalk, at the moment of writing on windows it is supported up to binwalk 2.1.1,
sources of binwalk_2.1.1 are supplied inside the binwalk_windows folder. To install it on Windows just run "python setup.py install"

## Acknowledgments

Thanks to these projects:

* Binwalk - https://github.com/ReFirmLabs/binwalk

* QHexEdit2 - https://github.com/Simsys/qhexedit2

* QT5