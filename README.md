There are two primary code bases for this project, the frontend and backend.
First, you need to download the frontend from this repository to your local machine.

Open the codebase in VS Code
Open the terminal in VS Code
Navigate to the install folder location using cd

Use the following commmands:
npm install
npx expo start

Expo Go will the ask where you want to emulate the appliation. You can use the web, apple, or andriod.
For our testing, we have used Andriod by pressing 'a'

We use Andriod Studio. 
The link to install Andriod studio can be found here: https://developer.android.com/studio
You will click "more actions" and "Virtual Device Manger"
In VDM you will see the current installed phones. Add a new phone.
Andriod Studio will come preinstalled with a Pizel 3a. This does not meet the minimum requirements to run the application. 
I suggest using a Google Pixel 7.
You need to have an Andriod running Android 11 or greater.

Warning: you may need an expo go account to start the application.
The backend will automatically be pulled from our MangoDB account through Railway.


Creating a user:
To create a new user navigate to the profile tab in the bottom right of the screen.
Click sign in and go to the "Register" tab.
Type any username, email, and password.
To sign in, you must refresh the application by pressing 'r' in the terminal where you orignally pressed 'a' to start the application.
This will refresh the database and you will now be able to sign into your new account.

