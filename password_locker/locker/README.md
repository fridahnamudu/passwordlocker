 Password Locker

## Built By [Fridah Joy Namudu](https://github.com/fridahnamudu/)

## Description
Password Locker is a terminal run python application that allows users to store details i.e. usernames and passwords of their various accounts.

## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like:
* To create an account with my details - log in and password
* Store my existing login credentials
* Generate a password for a new credential/account
* Copy my credentials to the clipboard

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./password_locker.py** | Welcome, choose an option: ca-Create Account, log-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your username and password |
| Display prompt for login in | **Enter: log** | Enter your username and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, ex - exit |
| Display prompt for creating an account | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## SetUp / Installation Requirements
### Prerequisites
* python3
* pip
* pyperclip


### Cloning
* In your terminal:
        
        $ git clone https://github.com/fridahnamudu/passwordlocker
        $ cd password_locker

## Running the Application
* To run the application, in your terminal:

        $ chmod +x run.py
        $ ./run.py
        
## Testing the Application
* To run the tests for the class file:

        $ python3 ./user_test.py
        
## Technologies Used
* Python3.6

## License
MIT &copy;2017 [Fridah Namudu](/)

