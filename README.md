# Windows-PE-Image-encryption-
PE encryption pitfalls 

To encrypt a Windows PE Image, it is not just as essy tp fully encrypt it, because that breaks the OS loader.

## Section 1
Section overview
https://learn.microsoft.com/en-us/windows/win32/debug/pe-format



## TLS section
Thread Local Storage, a simple concept that allows each thread to have a seperate memory section, accesible through a single C++ variable name... 
