
Learning Projects

A collection of small projects created while learning Python, JavaScript, HTML, CSS, SQL, and graphical user interface development. The repository includes browser-based exercises as well as a larger vehicle inventory application with database integration.

Projects

Car Inventory Manager

A Python application for managing a vehicle inventory. Vehicle data is stored in a SQLite database and can be accessed through either a command-line interface or a Tkinter desktop interface.

Features include:

Adding and listing vehicles

Input validation

Deleting selected vehicles in the GUI

Persistent storage with SQLite

CSV seed data

Light and dark interface themes

Tabular command-line output

Technologies: Python, SQLite, Tkinter, CSV, Tabulate

Age Check

A browser-based age checker that evaluates a user's input and displays a message for different age ranges.

Concepts: DOM manipulation, event handling, conditional statements, type conversion

Customer Orders

A JavaScript exercise that models users and orders with classes. Users can place orders and list their order history, while each order stores its item, price, and timestamp. Output is displayed in the browser console.

Concepts: classes, constructors, objects, methods, arrays, timestamps

Dice Roller

An interactive dice roller that generates random dice values and displays the matching dice images. The user can choose how many dice to roll.

Concepts: loops, random numbers, arrays, template literals, DOM updates

Digital Clock

A live 24-hour digital clock that reads the current system time and updates once per second.

Concepts: Date objects, string formatting, setInterval(), DOM updates

Password Generator

A configurable JavaScript password generator that creates a random password from selected character groups, including lowercase letters, uppercase letters, numbers, and symbols. The generated password is displayed in the browser console.

Concepts: functions, parameters, validation, conditional expressions, loops, random selection

Payment and Subscription Check

A small form that checks whether a user selected the subscription checkbox and which payment method they chose.

Concepts: checkboxes, radio buttons, events, conditional statements, DOM manipulation

Temperature Converter

An interactive converter for Celsius and Fahrenheit values.

Concepts: form input, radio buttons, numeric conversion, calculations, formatted output

Running the browser projects

Open the relevant project's index.html file in a web browser. No installation or build process is required.

For projects that write their results to the console, open the browser's developer tools and select the Console tab.

Running the Car Inventory Manager

Requirements:

Python 3

Tkinter, normally included with Python

tabulate for the command-line version

From the car_inventory_project directory, install the external dependency:

pip install tabulate

Run the command-line interface:

python main.py

Or run the graphical interface:

python gui.py

The repository already contains the SQLite database used by the application.

Repository structure

learning-projects/
├── ageCheck.js/
├── car_inventory_project/
├── customerOrders.js/
├── diceRoller/
├── digitalClock.js/
├── passwordGenerator.js/
├── paymentCheckbox.js/
└── tempMeasure.js/

Purpose

These projects document my learning progress and provide practical examples of programming fundamentals, object-oriented programming, browser interaction, data validation, database access, and desktop interface development.
