While
=====

_Some code katas centered on while loops_

Do Nothing
----------

Create a while loop that does nothing.

Create the simplest possible while loop that does nothing.

Read the File
-------------

Create a while loop that reads each line of a file, printing
each line to standard out.

Keep Asking
-----------

Create a while loop that keeps asking for user input until the
user enters "yes."

Create a while loop that keeps asking for user input until the
user enters either "yes" or "no."

Approximate Square Root
-----------------------

Apply the Babylonian Method to approximate the square root of
two using scaled integers.

Hint: use the fact that sqrt ( 4 x ) = 2 sqrt ( x ) to scale
appropriately.

Given a square S and a guess R0 for the square root of S, an
integer formula for the next better guess R1, based on the
Babylonian method might be

R1 = (R0 + S / R0) / 2

where / indicated _integer_ division or _floor_ division.

In Python 3, the formula could be represented

    R1 = (R0 + S // R0) // 2
