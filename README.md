# User_Sign-Up_and_Login_Form_created_with_Python
Used Python to build a sign-up and login form for users

Started by creating a text file named Credentials.txt that contain a dictionary of user Credentials, usernames and passwords.

Next, I built the login function.
  - Needed to take 2 inputs, name and password
  - Ask the user to enter their username and password
  - Search if the username already already existed in the Credentials.txt file
    - If the username was found in the file, then check if the entered password was correct for this user and then return a welcome statement for the user
    - If the username was found in the file, but the password entered was not correct for the user:
      - The user is prompted to reenter the password until they enter the correct answer
      - Then a welcome statement is returned
    - If the username was not found in the file:
      - Display the statement "Username does not exist. Please create an account"

Then I design up the sign up function.
  - Needed to take 2 inputs, newName and newPassword
  - Ask the user to input their username
  - Check to see if the username already exists in the Credentials.txt file
    - If the username already exists:
      - The user is prompted to enter a new username to use instead until an original username is entered 
    - If the username enetered is original:
      - The user is prompted to create a password for their account
      - Then the username and password are appended into the Credentials.txt file
      - Display the statement "Account created successfully" once appropriate credentials have been entered

  
