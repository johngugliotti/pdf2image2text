 

---------------------
--- MAC-Specific ---- 
---------------------
### brew install poppler    https://formulae.brew.sh/formula/poppler
### brew install tesseract  https://formulae.brew.sh/formula/tesseract


--------------------------------
------ Windows -----------------
--------------------------------

Poppler:
-------
Windows users will have to build or download poppler for Windows. 
I recommend @oschwartz10612 version which is the most up-to-date. 
You will then have to add the bin/ folder to PATH 
Alternatively: use poppler_path = "C:\path\to\poppler-xx\bin" as an argument in convert_from_path.

Tesseract:
---------
Download tesseract exe from https://github.com/UB-Mannheim/tesseract/wiki.

Install this exe in C:\Program Files (x86)\Tesseract-OCR

Open virtual machine command prompt in windows or anaconda prompt.

Run pip install pytesseract

To test if tesseract is installed type in python prompt:

import pytesseract

print(pytesseract)


https://stackoverflow.com/questions/46140485/tesseract-installation-in-windows


```pip install pdf2image```
```pip install pytesseract```