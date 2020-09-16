# twin-firmware-updater-qt

## Workflow
* Use Python 3.5 or 3.6
* Install **fbs**, **pyqt5** and **qt-designer**
* After creating UI with qt-designer,
* `pyuic5 -x uifile.ui -o test.py`

## Creating Installer

* Create a directory for the application
* `fbs startproject`
* In *src/main/python/* replace *main.py* with your code generated above.
* Check your program with `fbs run`
* Finally, `fbs installer`

## Useful Links
1. [Basics of PyQt](https://www.learnpyqt.com)
2. [Packaging Tutorial (fbs)](https://libraries.io/github/mherrmann/fbs-tutorial)
3. [PyQt Tutorial](https://www.youtube.com/playlist?list=PLzMcBGfZo4-lB8MZfHPLTEHO9zJDDLpYj)
4. [Advanced PyQt UI Examples](https://www.youtube.com/user/VFXtestingWMP)
