# morse_code_encoder
Implementation of a Morse Code Guide and Encoder to make morse code
decoding and learning easy for users, implementing Tkinter modules
for an interactive and user-friendly GUI [Graphical User Interface]
1 - The project is a working prototype of a morse code encoder .
2 - The objective of this project is to help people learn and encode morse
code messages.
3 - The project starts with a frame of start and exit buttons to navigate
through the interface.
4 -The start navigation takes to a frame with multiple access options
like :
1-Alphabets
2-Fun Facts
3-Phrases
4-Encode message
5 -The Alphabets button navigates to a frame with the morse code for each
alphabet which is useful for the user to learn morse alphabet by alphabet.
6 -The Fun Facts button navigates to a frame with interesting fun facts
regarding morse language which is a must read.
7 -The Phrases button navigates to a frame with buttons with common
phrases which when clicked gives the morse translation of the phrase.
8 - The ‘Encode’ message frame helps to encode any message to morse code
by asking the user to input the message and then displaying the
appropriate morse translation to the user.
9 - Each frame has a previous button navigation to help the user navigate
through the interface efficiently.
TECHNOLOGY USED/MODULE WISE DESCRIPTION:
1 - Tkinter: This module is imported for interactive GUI with coloured
frames, buttons and labels so as to make the prototype attractive as well
as efficient.
2 - Pillow- This module is used for importing images for the interface to
make it more user-friendly and attractive .
3 - Object-Oriented Programming- The concept of encapsulation is used to
combine the code into a class. Objects of the class are created and
methods are called using those objects.

4 - File Handling - The concept of file handling is used for displaying
fun facts as they are previously stored as a text file and then imported
in the code so that when the fun facts button is clicked it displays the
text file in the read mode.
5- Dictionary - Dictionary is used to store the morse codes for alphabets
as well as numbers and is used in encoding custom text messages .
6- List - Lists are used in user-defined function clear_widgets() to
append all the buttons,images,labels of the previous frame so that the
clear widget function can traverse through the list and destroy all the
previous frame widgets so that the next frame widgets can be displayed on
clicking the next button.
