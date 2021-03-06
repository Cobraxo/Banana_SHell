# Banana_SHell
  
  Compatible with distributions on **GNU Linux** and **MacOS**

  ![images/Banana_SHell_view_banana_command](/Images/Banana_SHell_view_banana_command.png)

## Features
  
  * Support all of your commands, like **ls**, **mkdir**, **pwd**, ... All ! ^^
  
  * He support also **Ctrl-C**, and **Ctrl-D** to exit the shell
  
  * Also we support all of Controls, like **Control-R**, etc
  
  * There is **auto completion**
  
  * You can do pipe, like that **ls | wc**, or what you want
  
  * We can do many commands in only one line ! With **;** like **mkdir banana ; cd banana**
  
  * Environnement variable can be change, create with **export**, **echo**, or delete with **unset**
  
  * Specific commands, are **help** and **banana**
    * **exit** command, to exit the shell
    * **cd** command, if you type just cd, you gonna home directory
    * **help** command, show you specific command, if you forgot it
    * **banana** command, show the Author (Me), date of the last update, and my github
    * **version** command, get the current version
    
   ![images/Banana_SHell_view_famous_command](/Images/Banana_SHell_view_famous_command.png)
    
## Make
  
  * To install the Banana SHell, on your computer, type **make install**
  * To uninstall the Banana SHell, type **make uninstall**
  * To compile Banana SHell, type **make**
  * To clean ObjectFiles directory, type **make clean**
  * To count number of line the project contains, type **make line**
  
  ## PS:
  * make line, was for show me how I reduce the code, because ***less is better !***
  * **ObjectFiles** directory, is **create by Makefile**
    
## HELP
  If you have any errors with readline library, try this: sudo apt-get ```sudo apt-get install libreadline6 libreadline6-dev```
    
## Diagram Of Codes
  
  ![images/Banana_SHell_Diagram](/Diagram/Banana_Shell_Diagram.jpg)
