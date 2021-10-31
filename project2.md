[Back to Portfolio](./)

Movie Ticket Booking System with GUI
===============

-   **Class:** Human-Computer Interaction (CSCI 434)
-   **Grade:** TBD
-   **Language(s):** Visual Basic
-   **Source Code Repository:** [HCI-Movie-Ticket](https://github.com/Xcar17/Portfolio-HCI-Movie-Ticket)  
    (Please [email me](mailto:cror93@gmail.com?subject=GitHub%20Access) to request access.)
-   **Authors:** Carlos Ocasio and Nathan Satterfield

## Project description

This application is a redesigned version of my CSCI 335 project. The application is used to interact with customers who are looking to purchase movie tickets. The new features of this program allow customers to choose their desired film, time of day, number of tickets, and seating options. Another notable new feature is the ability to search for the most economical movie ticket prices in the area. Once selections are made the customer will be able to purchase and print their ticket. This new application includes a graphical user interface, as the previous version uses a command line-based interface. 

My contribution to this project includes creating and implementing the Greeting, SelectMovie, SelectDay, SelectTime, SelectTickets, ReviewOrder, SelectPaymentMethod, PaymentInformation, and Receipt screen.

Nathan's contribution includes creating and implementing the SelectSeats, ReviewOrder2, and TicketPrint screen. In addition to this, Nathan assisted with the input validation across all screens.

## How to compiles / run the program

In order to run this application please download the Visual Studio program. To install Visual Studio please follow the following [Microsoft guide](https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2019). Once you have downloaded Visual Basic, you may download the MovieTicket application release.

To run the application, open the MovieProject.sln with the Visual Basic program. This will build the project and allow you to test and edit the application. To run the project, press the Start menu on the top navigation menu (you can also press F5) while the project is open.

## UI Design

The first screen greets the user with a welcome message, and it is also used to display important messages about the application. Users can continue to the next screen by clicking on the continue button. The next screen will display the available movies playing in the area (See Figure 1). The user can choose between one of these movies by pressing the continue button. After selecting a movie the user must select a showing day, time and price (See Figures 2-4).


![screenshot](/HCI Movie/movies.JPG)
Fig 1. Screen Of Currently Showing Movies

![screenshot](/HCI Movie/days.JPG)
Fig 2. Screen Of Available Showing Days

![screenshot](/HCI Movie/time.JPG)
Fig 3. Screen Of Available Showing Times

![screenshot](/HCI Movie/prices.JPG)
Fig 4. Screen Of Available Showing Prices

After selecting the ticket prices/location the user is taken to a screen where they must select the number of tickets they wish to purchase. There are two types of tickets, one for adults and one for minors. The users can also see the total cost of the tickets on this screen (See Figure 5). Once the user confirms the amount of tickets, they can continue to the next screen by pressing the confirm button. After selecting tickets, the user is taken to the Select Seats screen (See Figure 6). On this screen the user must choose their seating arrangement in order to continue.

![screenshot](/HCI Movie/selecttickets.JPG)
Fig 5. Selecting Tickets Screen

![screenshot](/HCI Movie/seats.JPG)
Fig 6. Selecting Seats Screen

Once the user has selected their seating arrangement, they are asked to review their transaction (See Figure 7). This screen displays all the selections and the total
cost of the transaction. Users can also change their prior selections by pressing the edit buttons on the right of the screen (See Figure 7). After confirming the transaction, the user must select their preferred payment method and enter payment information that is valid. (See Figures 8-9). Once the payment information has been accepted a receipt will be printed to the screen (See Figure 10). In order to continue the user must confirm that they have reviewed the receipt. Finally, the user's tickets will be printed to the screen (See Figues 11). Once the user has confirmed that they received the tickets, they can press the continue button and the transaction will be finalized.

![screenshot](/HCI Movie/review.JPG)
Fig 7. Transaction Review Screen

![screenshot](/HCI Movie/payment.JPG)
Fig 8. Payment Option Screen

![screenshot](/HCI Movie/paymentinfo.JPG)
Fig 9. Payment Information Screen

![screenshot](/HCI Movie/receipt.JPG)
Fig 10. Transaction Receipt Screen

![screenshot](/HCI Movie/tickets.JPG)
Fig 11. Printed Tickets Screen

Figures 12-14 display how the application handles invalid inputs and errors. You can also see the alerts that are displayed if the user tries to change a prior selection, back out, or exit the application (See Figure 15).

![screenshot](/HCI Movie/noinfo.JPG)
Fig 12. No Payment Information Error

![screenshot](/HCI Movie/noseats.JPG)
Fig 13. No Seats Selected Error

![screenshot](/HCI Movie/notickets.JPG)
Fig 14. No Tickets Selected Error

![screenshot](/HCI Movie/exit.JPG)
Fig 15. Exit Prompt

## 3. Additional Considerations

This application does not represent the full release. The application was designed as a prototype to conduct a Usability, and thus it may contain some bugs.

[Back to Portfolio](./)
