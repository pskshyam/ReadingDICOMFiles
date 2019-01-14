# ReadingDICOMFiles

## Introduction

The *objective* of this notebook is to

1. Download [DICOM](https://www.dicomlibrary.com/dicom/) (.dcm) files from https://medistim.com/dicom and read them using Python
2. Display all dicom tags in these files.
3. Write the tags to a text file.

To accomplish this, I am going to use a `pydicom` package from python to read DICOM (.dcm) files.

**pydicom** is a pure python package for working with DICOM files such as medical images, reports, and radiotherapy objects. 
Pydicom makes it easy to read these complex files into natural pythonic structures for easy manipulation. 
Modified datasets can be written again to DICOM format files.

If pydicom is not installed, it can be installed using command pip install pydicom

For more information on pydicom library,\
https://pydicom.github.io/pydicom/stable/getting_started.html
