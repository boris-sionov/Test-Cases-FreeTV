<!-- suite
id: @Se2808379
emoji: 
-->
# Registration



<!-- test
id: @Tb3bc0ef4
priority: normal
creator: boris103@gmail.com
-->
# Register a New User in FreeTV App

### Description:
Validate that a new user can register for a FreeTV account and is automatically logged in upon successful registration.

### Prerequisite:
* FreeTV app is installed and launched

### Steps:
1. Open the **FreeTV** app  
2. Start the registration process from the welcome or login screen  
3. Fill out the registration form with valid details  
4. Submit the form  

### Verifications:
* Registration completes without errors  
* Success message or confirmation screen is displayed  
* User is automatically logged into their new account  

### Expected Result:
* A new FreeTV account is created successfully, and the user is logged in

<!-- test
id: @T7ddf733e
priority: normal
creator: boris103@gmail.com
-->
# Verify Message and Buttons When Logging in with Non-Existing Account in FreeTV App

### Description:
Validate that when a user attempts to log in with a phone number not associated with any account, the app provides appropriate messaging and options.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a phone number that does not have an account  
4. Press **Send**  

### Verifications:
* A message appears:  
  `"No account found with this phone number. Would you like to join FreeTV?"`  
* Two buttons are displayed:  
  * **Join to FreeTV**  
  * **Try another number**  

### Expected Result:
* User is informed that the account does not exist and is given the option to join FreeTV or try another number

<!-- test
id: @Tbdeb843b
priority: normal
creator: boris103@gmail.com
-->
# Verify "Try Another Number" Button Behavior in No Account Found Message

### Description:
Validate that when a user attempts to log in with a non-existent account and selects **Try another number**, they are returned to the login screen with the input field cleared.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a phone number that does not have an account  
4. Press **Send**  
5. Press the **Try another number** button  

### Verifications:
* User is navigated back to the login screen  
* Phone number field is cleared and ready for new input  

### Expected Result:
* User can attempt login again by entering a different phone number

<!-- test
id: @T6cb7a649
priority: normal
creator: boris103@gmail.com
-->
# Verify "Join to FreeTV" Button Behavior in No Account Found Message

### Description:
Validate that when a user chooses **Join to FreeTV** after attempting to log in with a phone number that has no account, they are directed to the registration process.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a phone number that does not have an account  
4. Press **Send**  
5. Press the **Join to FreeTV** button  

### Verifications:
* User is navigated to the registration screen  

### Expected Result:
* User can proceed with creating a new FreeTV account

<!-- test
id: @Td45d2414
priority: normal
creator: boris103@gmail.com
-->
# Verify Registration Attempt with Existing Account in FreeTV App

### Description:
Validate that a logged-out user who attempts to log in with a non-existent phone number can choose **Join to FreeTV** and start the registration process.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a phone number that does not have an account  
4. Press **Send**  
5. Press the **Join to FreeTV** button  

### Verifications:
* User is navigated to the registration screen  

### Expected Result:
* User can proceed with creating a new FreeTV account

<!-- test
id: @Tf5e94906
priority: normal
creator: boris103@gmail.com
-->
# Verify "Try Again" Button Behavior After Registration Attempt with Existing Account

### Description:
Validate that when a user attempts to register with a phone number that already has an existing account and selects **Try again**, they are returned to the registration page with empty fields to retry.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Select **Join to FreeTV** to open the registration screen  
4. Enter a phone number that already has an existing account  
5. Fill in the remaining required registration fields with valid data  
6. Press **Send** or **Register**  
7. On the `"You already have an account"` message screen  
8. Press the **Try again** button  

### Verifications:
* User is returned to the registration page  
* All fields are cleared for new input  

### Expected Result:
* User can attempt registration again with a different phone number

<!-- test
id: @Te5139a05
priority: normal
creator: boris103@gmail.com
-->
# Verify "Login" Button Behavior After Registration Attempt with Existing Account

### Description:
Validate that when a user attempts to register with a phone number that already has an existing account and selects **Login**, they are redirected to the login screen with the phone number pre-filled.

### Precondition:
* User is logged out

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Select **Join to FreeTV** to open the registration screen  
4. Enter a phone number that already has an existing account  
5. Fill in the remaining required registration fields with valid data  
6. Press **Send** or **Register**  
7. On the `"You already have an account"` message screen, press the **Login** button  

### Verifications:
* User is navigated to the login screen  
* The phone number field is pre-filled with the previously entered number  

### Expected Result:
* User can log in directly with the existing account credentials

<!-- test
id: @T605d4d50
priority: normal
creator: boris103@gmail.com
-->
# Verify Rejected Login via SMS Link

### Description:
Validate that when a user rejects the login request from the SMS link, the FreeTV app displays a rejection message and keeps the user on the login screen.

### Precondition:
* User is logged out  
* Valid registered phone number exists

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a registered phone number  
4. Press **Send**  
5. On the phone receiving the SMS, open the link in the message  
6. Select **Reject login**  

### Verifications:
* A message appears in the FreeTV app stating that the login request was rejected  
* User remains on the login screen  

### Expected Result:
* Login is not completed  
* User can retry login or enter a different phone number

<!-- test
id: @T70e36815
priority: normal
creator: boris103@gmail.com
-->
# Verify Successful Login with Registered Account

### Description:
Validate that a user with valid account credentials can successfully log in to the FreeTV app and access the main page.

### Precondition:
* User is logged out  
* Valid phone number and account credentials exist

### Steps:
1. Open the **FreeTV** app as a logged-out user  
2. Press **Enter to the service**  
3. Enter a registered phone number  
4. Press **Send** or **Continue**  
5. Enter the correct verification code (OTP) or password if prompted  
6. Complete the login process  

### Verifications:
* User is successfully logged into their account  
* Main page of the FreeTV app is displayed  

### Expected Result:
* Login is successful and the user is taken to the main page with their account active
