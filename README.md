# Python Project: Order Management System
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

The Restaurant Order Management System is a project aimed at streamlining the order management process in restaurants. The current manual system is prone to errors and inefficiencies, leading to delays in order processing and customer dissatisfaction. The objective of this project is to develop a software solution that automates the order management process, improves accuracy, and enhances the overall customer experience.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Modules Used:**

Tkinter - Tkinter is a python module that provides a simple and efficient way to create Graphical User Interfaces using the Tk GUI Toolkit. It is a wrapper around the Tk toolkit which is written in C and is native to Python Interpreter

Time - The time module is a built in Python library that provides functions for working with times and dates. It includes functions for getting the current time, measuring time intervals and formatting time strings

FIledialog - The filedialog module in Tkinter provides convenient functions for creating file dialogs in Python applications. Using askopenfilename, developers can prompt users to select a file for opening, while asksaveasfilename enables the selection of a file and location for saving. These functions streamline file interaction in a platform-specific manner, seamlessly integrating with the native file dialogs of different operating systems.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Defined Functions:**

save_order_details(): Saves customer and order details to a specified text file, including customer information, ordered items, and the total bill.

apply_label_style(): v

apply_button_style(): Applies a common style to Tkinter labels, buttons, entry boxes like font and background color.
apply_entry_style(): ^

create_frame(): Creates and returns a Tkinter frame with a specified background color.

menu_page(): Displays the Italian menu, allowing the user to select items and calculate the total bill before proceeding to the payment page.

payment_page(): Displays the order details and total bill, allowing the user to finish the payment and save the order details.

welcome_page(): Initializes the main Tkinter window for the restaurant order management system, allowing users to enter their details and proceed to the menu.

calculate_bill(): Takes ordered items and multiplies count of items with the price of the item and adds to the final bill amount along wit GST calculation of 5%.

finish_payment(): Calls and displays the customer and bill details when the Finish button is clicked.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Algorithm:**

The user interface of the Restaurant Order Management System is built using Python (Tkinter GUI). The frontend is designed to be intuitive and user-friendly, allowing restaurant staff to easily navigate and interact with the system. Tkinter is used to enhance the user experience by providing dynamic and interactive elements. Flowchart image attached.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Results and Discussion:**

The implementation of the Restaurant Order Management System can lead to improvements in efficiency of restaurant staff.

Increased Efficiency
The system significantly improved the efficiency of the order management process. Orders can be processed faster and more accurately, reducing errors and delays. This will lead to improved customer satisfaction and increased revenue.

Customer Insights
The system generated valuable customer insights through data analysis. It captured order history, which can be used to personalize the dining experience and improve customer retention.

Future Enhancements
Based on the findings, future enhancements to the system can include integration with online ordering platforms, loyalty programs, and automated reporting for better business analytics. It can also be integrated into micro bill machines to streamline the billing process.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
