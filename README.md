# DES
Des program in python

This Des program is for python 2.
-Import the following libraries
-import binascii
-import base64
-import pyDes
-import sys
-from tkinter import *
-from tkinter import messagebox
-from tkinter import filedialog
-from tkinter import scrolledtext

8 bytes of key is used.
if key is less then 8 bytes additional padding is used where the character "A" is padded to the key.
you can change if you want to add any other character padding from the function padding.

-padding for text used is pkcs5
*****************************************************************************************************************
to run the program:
    python des.py
    
-insert plain text and key to get encrypted text
-insert encrypted text and key to get back the plaintext
-wrong decryption will give an error because text padding wont be satisfied
