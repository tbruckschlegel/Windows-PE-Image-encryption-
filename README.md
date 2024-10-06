# Windows-PE-Image-encryption-
PE encryption pitfalls 

To encrypt a Windows PE Image, it is not just as essy tp fully encrypt it, because that breaks the OS loader.

## Section 1
Section overview
https://learn.microsoft.com/en-us/windows/win32/debug/pe-format

## adding new entry section
First of all, we need to add a new code entry point and then we can encrypt all of the PE Image, nearly all of it 🤣

## TLS section
Thread Local Storage, a simple concept that allows each thread to have a seperate memory section, accesible through a single variable name.

Stay tunes for code to come!
