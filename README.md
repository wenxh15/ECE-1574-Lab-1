# ECE-1574-Lab-1
This lab focuses on the following learning objectives:  Write complete C++ programs to solve engineering problems
Procedure:
This week we will be working on writing some basic C++ programs that print different messages to the screen. We will be focusing on writing simple messages to the screen. You can use the simple Hello World program as a starting point. The thing to focus on is the line containing the word cout. This tells C++ to write something to the screen. The word endl stands for end of line and will essentially print a newline or a return character. We will be getting into all the details about all of this very soon in class. Today it suffices if you can simply copy, paste and make some edits.

#include <iostream>
using std::cout;
using std::endl;

int main()
{
    cout << "Hello World!" << endl;

    return 0;
}
The important part of the code above is the line cout << "Hello World!" << endl;
cout is the standard output stream. By default it will print to the console. It will print any set of characters that appear in between the set of double quotes (""). This can contain spaces, letters, numbers, symbol. There are two special escape characters that could help with this lab. \t mean tab and \n means newline. So cout << "\tDave"; Will print out Dave with a tab, 4 or 5 spaces, before. cout << "dave\n"; Will print out Dave and then a newline character or like pressing return or enter on the keyboard. You may also use endl, that's end and letter l (ell), not a 1. endl includes both a newline character and flushed the output buffer. We'll discuss this more later.

We will be print four different messages to screen. You can simply put them all in the same program one after another. Or you can create 4 different programs. Please note that C++ only allows one main function, so you cannot have 4 main functions in one files. You won't be able to compile it. Please don't hesitate to ask for help at any point during the lab. For more information on compiling see the notes page on the Command Line Compiling

So open Notepad++ and use Powershell. Use the cd (change directory) command to move into the directory where you will be saving you cpp files. Then in Notepad++ get the Hello World file in and start working on the parts. I suggest saving your files without any spaces in the names. Don't forget to make sure the file is a CPP file, not an h or txt file.

Part 1:

Print a message like this one:

+----+
|Dave|
+----+
Instead of my name, you will put yours.

Part 2:

This time we are going to draw a face. Here is a face you can draw. If you would like to draw a different face, that is fine.

  /////
 | o o |
(|  ^  |)
 | [_] |
 |_____|
Part 3:

For this part, you will be printing a simple grid.

+---+---+---+
|   |   |   |
+---+---+---+
|   |   |   |
+---+---+---+
|   |   |   |
+---+---+---+
Part 4:

For this last final part, we are going to print a modified version of the grid from last time. We are going to print a stair steps.

            +---+
            |   |
        +---+---+
        |   |   |
    +---+---+---+
    |   |   |   |
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
