[Back to Portfolio](./)

Movie Ticket Booking System
===============

-   **Class:** Object-Oriented Programming (CSCI 335)
-   **Grade:** 100%
-   **Language(s):** Java
-   **Source Code Repository:** [Movie Ticket Booking System](https://github.com/Xcar17/Movie-Ticket-App)  
    (Please [email me](mailto:cror93@gmail.com?subject=GitHub%20Access) to request access.)
-   **Authors:** Carlos Ocasio, Tyler Poor, and Paul Johnson

## Project description

This program is designed to interact with customers to produce a movie ticket. The features of this program allows customers to choose their desired film, time of day, and payment option. Once selections are made the customer will be able to purchase and print their ticket. Aditionally, the program will allow an employee with designated rights to manage the available movies, times, seating, and ticket prices. 

My contributions included creating and implementing the Greeting, Movie, SelectMovie and SelectTime, MyDriver classes. Additionally, I collaborated with Tyler Poor to validate the input of the ConfirmPayment, Print, and SelectPayment classes. Lastly, I collaborated with Paul to validate input on the EditMovie class.

Tyler Poor's work consisted of the design and implementation of the ConfirmPayment, Print, and SelectPayment classes. 

Paul Jonson's  work consisted of the design and implementation of the EditMovieScreen class. 

## How to compiles / run the program

In order to run this program, you need to install a Java Development Kit (JDK) which includes the Java runtime needed to run this application. You may download a Java JDK by following [this link](https://www.oracle.com/java/technologies/downloads/). After you download the Java JDK, please visit [this link](https://docs.oracle.com/javase/7/docs/webnotes/install/windows/jdk-installation-windows.html) for instructions on how to install the JDK and how to setup your Java environment. The instructions also include a very helpful troubleshooting guide. After the Java JDK is installed and setup you can download the TicketBookingSystem directory from the repository. You are now ready to compile and run the program.

- In order to compile the program, run the Command Prompt and open the "src" directory inside of the "TicketBookingSystem" directory. If your TicketBookingSystem directory is in the Downloads directory the command will look like this "cd Downloads/TicketBookingSystem/src". 
- Once you are in the "src" directory, enter "javac csu/csci325/MyDriver.java" to compile the program.
- Once the program has been compiled, you may enter "java csu.csci325.MyDriver" to run the program.

## UI Design

This Movie Ticket Booking application uses a command line user interface. Users are prompted to enter a number that corresponds with an available selection. All available options are displayed to the user at all times. This was done in order to prevent users from having to memorize commands in order to use the application.

After running the application, the user is greeted with a message that was implemented for grading purposed of the assignment. The message informs the grader that they can access the manager side of the application by typing the “12345” command at the initial screen. This message has to be removed and the password changed before implementing this application to a real-world scenario. (See Figure 1).

Figure 1 displays the greeting and all the user selections. First the user is greeted and asked to select a movie from one of the available options. In order to continue, the use must select a number that corresponds to the movie that they wish to see. After confirming their selected movie, the user must then select a showing time. Once this is done, the user must select a payment method and enter their payment information (See Figure 1).

Before completing the transaction, the user is asked to confirm the transaction. Once this is done the user is thanked for their purchase and they receive the ticket for their movie (See Figure 2).

Figures 3 and 4 demonstrate how the application responds to errors and invalid inputs. When entering a number smaller or larger than the options available, an error message will inform the user that they must enter a number between the available choices (See Figure 3). If the user input does not match the specified length for every prompt, an alert message will inform them that the input is invalid and will ask them to try again (See Figure 4). Notice that on Figure 4, the user is still able to complete the transaction despite all the errors.


![screenshot](/Ticket-Images/java1.JPG)
Fig 1. Making Selections

![screenshot](/Ticket-Images/java2.JPG)
Fig 2. Completing Transaction

![screenshot](/Ticket-Images/javaerror1.JPG)
Fig 3. Making Selection with Errors

![screenshot](/Ticket-Images/javaerror2.JPG)
Fig 4. Completing Transaction Despite Errors


## 3. Additional Considerations

This Movie Ticket Booking application was developed on Neatbeans using Java version 8 on a Windows system. It was a group project developed by Carlos Ocasio, Tyler Poor and Paul Johnson.


[Back to Portfolio](./)
