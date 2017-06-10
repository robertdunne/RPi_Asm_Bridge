Assembly Language Using the Raspberry Pi: A Hardware Software Bridge
--------------------------------------------------------------------

The publisher makes no warranty, express or implied, with respect to the material contained herein.
The program listings, examples, and other information presented in this book are distributed on an
“as is” basis, without warranty. Although every precaution has been taken in the preparation of this
book, neither the author nor Gaul Communications shall have any liability regarding its use.

This book contains over 50 program listings as examples of ARM, VFPv3, and NEON coding.
The following command on the Linux command line will download the RPi_Asm_Bridge directory:

~$ git clone https://github.com/robertdunne/RPi_Asm_Bridge.git

All of the files are named according to the book's listing ID number. They can then be copied as
needed to the appropriate source file name. For example, the model.s source file in Lab 1
is obtained by entering the following:

~$ cp RPi_Asm_Bridge/Listing_1_2.txt model.s

The ls and cat commands are useful to list the contents of the
directory and the copied model.s source code, respectively.

~$ ls RPi_Asm_Bridge
~$ cat model.s

Warning: The assembler source code that appears in this book and is available for
download is for learning to program in assembly language. Some of these subroutines are
incomplete and even contain problems that need to be corrected in exercises at the end of
the labs. No guarantee of their commercial utility is expressed or implied.

