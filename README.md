# TestTaskAutomationKotlin

Implement Simple Android application with the following screens (Kotlin or Java):



1. Login Screen (contains Application Name, only 2 input fields: login, password and 1 button: login) — will login any user with email domain @gmail, reject any login without @gmail domain, any password more than 3 chars length is acceptable

2. Devices screen (Recycler view with 3 random square pictures and 1 button on the top of the screen — settings). Only settings button is clickable.

3. Settings screen (Only 2 buttons: back to devices, logout).



For that Application, please create a test project using Page Object pattern.



Please implement the following 5 test cases using your Page Objects and Test class:



1. Login with valid user data, open settings, go back to devices, logout

2. Try login with non-gmail user data, assert that it is not possible

3. Try login with empty user data, assert error that it is not possible

4. Login with valid user data, click on each picture and make sure, nothing happens

5. Open Login screen and check that application name is valid



After work is done please create a report in English:

1. How long it took to implement the application

2. How long it took to implement automated test cases

3. How long it took to write a report



Useful notes:

1. If you use Android native automation — prefer UIAutomator 2

2. If you use Appium — you may want to use TestNG to create a test suite to run tests

3. If you don’t have Android device — Android x86 emulator is fine

4. If you are not able to run Android x86 emulator in your local environment — create a web application, with web server at localhost and use Appium to automate everything as described in Task



It is a plus if:

1. You have made nice OOP structure

2. You have implemented it using Appium

3. Any additional features implemented in the application and covered by automated test case

4. Test cases were implemented before application implementation —TDD

5. Everything is implemented in Kotlin

6. You have implemented Appium PageFactory locators in your PageObjects
