Thank you for choosing Ocean API, We hope you have a great exploiting experience! (Created on 12/13/2021):

*//* HOW TO USE OCEAN API INSIDE OF A PROJECT? *//*
First, include the API's internal namespace called "Ocean".
(Make sure to include using OceanAPI; before reading ^^).
Call the function 'Ocean' at the top of public Form1 Initialize.
Example: Ocean oAPI = new Ocean(); oAPI can be renamed.
There are 6 internal functions included inside of OceanAPI.
Attach, Execute, Update, CloseRoblox, CreateFolders, ClearScript.
To use a function, use the var 'oAPI', example: oAPI.Attach(); or oAPI.Execute("print hi").
In order to update the DLL, use oAPI.Update(); (suggested to create a new btn with 'update').

*//* HOW TO ADD SIMPLE COMMANDS INSIDE OF A PROJECT? *//*
Use the defined variable 'oAPI.Execute' but don't use any string (yet).
Make 2-4 strings, example: string print = "print('watever u want here')".
(Make sure string has your script command in order to execute it).
Make a btn, and paste this code: oAPI.Execute(print); bool complete = true;
For each command you make, change the 'print' to the string name.
Do not use loadstrings or HttpGet, only use the raw script data.

*//* HOW TO USE CUSTOM MESSAGE WHEN ATTACHED? *//*
(Please do not use Loadstrings, Only use Raw Script Data).
A custom message can be a GUI (game user interface) or a old style GUI notification. As long as it's not obfuscated, loadstring format, or even converted into base(encoded, you can make a message. 
Paste this code: string msg = "print 'helo'" oAPI.Execute(msg); This sends 'helo' into the console.
print 'helo' can be replaced with any lua-based script as long as it meets the requirements above.
NOTE: BECAUSE YOU ADDED A CUSTOM MESSAGE WHEN ATTACHED, THAT DOES NOT MEAN YOU OWN THE API OR DLL. YOU CANNOT ADD YOUR OWN CREDITS (sure you may add it for the custom lua message script).
