# Test Cases 
Author: Nelson Chen, Ye Tian, Chudong Pan, Congcong Che //**Team 31**

|Test# |Functionality |Scenario |Description |Tested by |Automated? |Device1 |Device2 |Device3 |Note |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Startup  |App loads   |After tapping on app icon, the welcome screen loads within 2 seconds. |  |  |  |  |  |  |
| 2 | Login | An existing player can log in | Login with existing username (Type *player1* and hit "LOGIN" button). The player will come to next screen showing "SDPGuessIt". | | | | | | |
| 3 | Login |User with invalid username cannot login | Login with nonexistent username (Type *failusername* and hit "LOGIN" button). The app will display error message "username not found". | | | | | | |
| 4 | Create new player | A user can create new player. |On Sign Up screen, enter *Email*, *Username*, *First Name*, *Last Name*, hit SUBMIT button, you should get an confirmation message: "new player successfully created". | | | | | | |
| 5 | Create new player  | Incorrect email  | Sign up with an invalid email address: "fakeemail". The app will display error message: "Please use valid email address". | | | | | | |
| 6 | Create new player  | Username too long  | Sign up with a Username longer than required length: "abcdefgh123456789100000000". The app will display error message: "username too long". | | | | | | |
| 7 | Create new player  | Username too short  | Sign up with a Username shorter than required length: "a". The app will display error message: "username too short".| | | | | | |
| 8 | Create new player  | Username already taken | Sign up with a Username already taken: "player1". The app will display error message: "Username already taken, please choose another one.".| | | | | | |
| 9 | Create new player  | Input missing | On the "Sign Up" screen, hit the "SUBMIT" button without type anything. All fields should be indicated with the error messages: "Please specify a valid email", "Please specify a valid username", "Please specify your first name", and "Please specify your last name". | | | | | | |
| 10 |   |   |   |  | |  |  |  |  |
