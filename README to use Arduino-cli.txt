To install the arduino cli, you need to download the cli

for more information check this : 
https://arduino.github.io/arduino-cli/installation/

For windows place the Arduino-cli.exe file in Windows/System32/ so that you will access it 
throughout or do it by providing the PATH if you know to do it.

open Terminal and check is it installed : $ arduino-cli

you will see the list of commands

NOW :

to create a New project :
arduino-cli sketch new test

now head to the directory with a IDE(Atom/Sublime) and code it.

To check the installed libraries :
arduino-cli lib list

To view the list of boards attached to PC :
arduino-cli board list

To compile the code :
arduino-cli compile -b arduino:avr:uno test

To upload the code :
arduino-cli upload -p COM26 -b arduino:avr:uno test

To search for libraries for example to search for blynk :
arduino-cli lib search blynk

To install the library blynk, properly write the name of the library :
arduino-cli lib install blynk


SIMPLE! EXCITING! FUN!
