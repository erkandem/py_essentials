# python-essentails
A collection of simple python algorythms and functions.

# File handling (filehandler.py)
required python modules:
    os (standart)
functions:
    singlePull(file, line)             reads a single line from a file
    singlePush(file, line, text)       writes text into any single line of a file
    getLenght(file)                    returns the amount of lines in a file
    delete(file)                       deletes a file
    create(file)                       creates a file
    
# Printing with color (advancedPrint.py)
required python modules:
    os (standart)
functions:
    effect(effect)                     execute this to set the color effect or reset the color
                                       for the following text prints. (blue, red, bold, reset, ...)
    effectXY(x, y)                     very special custom printing effects. (look into the code)
    clean()                            cleans up the terminal by creating 100 empty lines.
    