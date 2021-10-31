[Back to Portfolio](./)

Guessing Game
===============

-   **Class:** Survey Of Scripting Languages (CSCI 301)
-   **Grade:** 100%
-   **Language(s):** Perl
-   **Source Code Repository:** [Guessing Game](https://github.com/Xcar17/Guessing-Game)  
    (Please [email me](mailto:cror93@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This script created in Perl is a Guessing Game where the user attempts to guess a number. The script generates a random positive number from a range of values determined by the user. The user will be given an option to quit the game after the first failed guess and after every third failed guessing attempt. If the user decides to quit the game without correctly guessing the number, the correct number will be printed to the screen before exiting the game.

## How to run the program

In order to run this script please download and install a verison of Perl on your system. Please follow [this](https://beginnersbook.com/2017/02/installing-perl-on-windows-mac-linux-and-unix/) guide on how to install Perl. 

After installing Perl and downloading the file from the repository, you must find the "projectOne.pl" file on your terminal. After locating the file enter the following:

```
perl projectOne.pl
```

## UI Design

This script uses a command line interface. Users are prompted to enter a number that corresponds with an available selection. All available options are displayed to the user at all times. This was done in order to prevent users from having to memorize commands in order to use the application.

After running the script, the user will be greeted with a welcome message and they will be prompted to enter what will be the maximum number to guess. Once a positive number has been entered the script will generate a random number between one and the maximum number selected. The user will be asked to guess the number until they answer correctly or give up. The user will be asked if they wish to exit the game after every third failed guess. After every guess, the application will notify the user if their guess was too high or too low. A successful game is displayed on Figure 1.

Figure 2 displays how the script handles invalid input and errors.

![screenshot](/Guessing Game/guessing1.JPG)
Fig 1. Successfully Guessing the Number

![screenshot](/Guessing Game/losing.JPG)
Fig 2. Failing to guess the Number

## 3. Additional Considerations

N/a


[Back to Portfolio](./)
