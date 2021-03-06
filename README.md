# PDF-Viewer
A **Pure Python PDFViewer**, which provides functionalities same as other famous PDFViewers. Following are the some of main features of this application

- Searching through text
- Table of contents
- Take notes and save them automatically
- Developed in pure python

## Why bother creating new PDF Viewer?
 I wanted to create an application that requires me to have a PDF Viewer with access to the source code in python. I searched the internet for a PDF Viewer written in Python, but all in vain. I couldn't find any reasonable result.
Hence, I decided to create my own PDF Viewer, that uses pure python packages.

## How to run?
Make sure you have installed these packages:

- PySimpleGUI
- PyMuPDF
- fitz

You can simple run this command to install all packages. First make sure you are in same directory as *requirements.txt*, then type:

`pip install -r requirements.txt`

This will install all the packages, then you have to simple run this command:

`python pdfviewer.py`

Given command will generate this screen:
![pdfviewer](https://user-images.githubusercontent.com/49767636/83327987-6d8eea00-a299-11ea-9e48-38486d1eccbd.png)


Now, you can open any book and enjoy reading.
![pdf](https://user-images.githubusercontent.com/49767636/83328464-a2e90700-a29c-11ea-88ee-7b93689df28a.gif)

## Notes
Well you can take notes as you go through the book. On the right side there a space for writing anything you want. There is a "Check Box" at the right hand corner make sure that box is checked, only then the note will be saved.

A file name like this "%PDF Filename%_notes.txt" will appear once you close the document. This file will look something like this:

![note](https://user-images.githubusercontent.com/49767636/83328822-5fdc6300-a29f-11ea-9f1f-374b00184fe3.png)

You can see how easy it is to navigate through this text file and see all the notes.

### Whats special about it?
Once you have taken the notes, then, whenever you open the same file again, all the notes will appear again with respective to there page number. If you take example of above given screenshot of the notes.txt, when I open the same file again you can see the notes:

![demonote](https://user-images.githubusercontent.com/49767636/83328967-353eda00-a2a0-11ea-8b01-cf960b719bbb.png)

Make sure you don't delete the text file that is created automatically by the PDFViewer.

## Language
I have used "Urdu" language for my application, but don't worry I will be converting the viewer into English and will add some more features also. 

## TODO
Following are some of the tasks that I am working on currently.

- Use English throughout the application
- Add zooming capability
- Add DocStrings and comments in the code
- Fix bugs in searching feature

## Special Thanks
I want to thanks [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) for developing such a great GUI-Framework in python.

