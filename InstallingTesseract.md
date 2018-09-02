## Installing Tesseract OCR

Click [here](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-setup-3.05.02-20180621.exe) to install Tesseract OCR

## Installing and configuring pytesseract

1. pip install pytesseract
2. Go to **C:\Anaconda3\Lib\site-packages\pytesseract**
3. Open the python file named **tesseract**
4. Delete the line below the "*# CHANGE THIS IF TESSERACT IS NO. . . .*" comment and replace it with:  
            *tesseract_cmd = r'C:\Program Files (x86)\Tesseract-OCR\tesseract'* 
5. Save your changes and you are done.
