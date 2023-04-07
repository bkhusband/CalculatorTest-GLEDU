RUNNING THE PROJECT:

This project was developed in Visual Studio 2017 using the ASP.NET framework and C#. It has been tested on several browsers but was primarily developed with Microsoft Edge. 

Visual Studio may need the ASP and Web Development extensions in order to run the CalculatorTest-GLEDU project. All code has been provided in text format to be viewed if any incompatibilies occur.

TASKS:

All of the following tasks have been evidenced in the project:

1.	Create an empty solution called CalculatorTest.
2.	Create a class library containing the interface above.
3.	Create a C# class to realize the interface as a C# class and implement the methods.
4.	Create unit tests to confirm the functionality performs as expected
5.	Create a simple web service that provides access to the calculator implementation 
6.	Create a Web App using Angular or a suitable alternative to provide a user friendly interface to invoke the Calculator operations
7.	Ensure the Calculator operations are performed in a modal popup which has a header and a footer
8.	Add functionality on the main web app page to be able to restyle the look and feel of the modal popup
9.	Ensure the web app can work on a variety of screen sizes and devices

The ISimpleCalculator.cs class file contains the public interface and the public class which realises that interface.
The class, SimpleCalculation contains the methods for simple calculations and returns the result.
These methods are referenced in the Calculator-GLEDU.aspx file which contains event listeners for the ASP web application. 
The Calculator modal popup can be opened through the press of a clearly labelled button which calls a ScriptManager. Within this modal, a user may enter two values into labelled text boxes and select the appropriate operator to complete the calculation. 
The web application imports a Bootstrap stylesheet and applies this styling to the modal window and user inputs. This adds some level of built in responsiveness for screen size scaling. The application has been tested on various screen sizes but has not been tested on mobile devices due to a lack of an emulator.
The user is also provided with some styling options to customise the application, allowing them to change the display of the buttons (text or symbols) and the font that is used on the form. 
Finally, an ajoining project named CalculatorTest-GLEDU.Tests has been added containing several simple unit tests which confirm the functionality of the app. 

FURTHER IMPROVEMENTS:
If I were to progress further with this app, I would make the following changes:
- AJAX could be used to complete calculations as, in the current version, the calls to the server force the page to refresh which closes and reopens the calculator modal.
- More complex operations and calculations could be performed such as percentage calculations or the inclusion of fractions 
- Further styling could be done to make the page more visually appealing. 
- More customisation options could be provided to the user.

