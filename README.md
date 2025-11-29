 # Week 7: Secure Authentication System
Student Name: Fathima Hudha Mohamed Ibrahim
Student ID: M01088116  
Course: CST1510 -CW2 -  Multi-Domain Intelligence Platform 
## Project Description
 A command-line authentication system implementing secure password hashing
 This system allows users to register accounts and log in with proper pass
 ## Features- Secure password hashing using bcrypt with automatic salt generation- User registration with duplicate username prevention- User login with password verification- Input validation for usernames and passwords- File-based user data persistence
 ## Technical Implementation
- Hashing Algorithm: bcrypt with automatic salting
- Data Storage: Plain text file (`users.txt`) with comma-separated values
- Password Security: One-way hashing, no plaintext storage
- Validation: Username (3-20 alphanumeric characters), Password (6-50 characters)
## Menu Display
- Shows a welcome message.
- Display a menu giving options 1-3
- Menu contains Register, Login, Exit.
- Runs in a loop so menu keeps showing.
- Expects user input (1-3).
- Program will act on the chosen option
