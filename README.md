Download link :https://programming.engineering/product/divassempbly-s-translate-the-c-program-you-wrote-to-do-division/

# Divassempbly.S-Translate-the-C-program-you-wrote-to-do-division-
Divassempbly.S (Translate the C program you wrote to do division)
Files to submit: divAssempbly.s

Time it took Matthew to complete: 15 mins

Translate the C program you wrote to do division in constant time into an assembly program called divAssembly.s.

The label for the dividend is dividend

4 bytes of space should be made for the dividend

The label for the divisor is divisor

4 bytes of space should be made for the divisor

Place the quotient in EAX

Place the remainder in EDX

Don’t forget that if you want to shift by a variable amount the shift amount must be placed in CL. Your assembly code won’t work if you try to place it in any other register.

AFTER the last line of code that you wish to be executed in your program please place the label done.

Make sure that there is an instruction after the done line and a new line after that instruction. If you don’t your output won’t match mine.S

IT IS OF VITAL IMPORTANCE THAT YOU NAME YOUR LABELS AS SPECIFIED AND MAKE THE APPROPRIATE AMOUNT OF SPACE FOR EACH VARIABLE! I will be using gdb to test your code and if your labels do not match then the tests will fail. You must also make sure to include the done label AFTER the last line of code you want executed in your program so that I know where to set break points.
