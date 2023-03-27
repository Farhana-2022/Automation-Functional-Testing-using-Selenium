The software that will determine the insurance rate of an individual based on their age, number 
accidents and their driving experience. The application requires the following mandatory input fields:
• Name (separated by First Name and Last Name)
• Address
• City
• Province
• Postal Code (Acceptable format: ANA NAN – where “A” is any alphabetic character and “N” is a valid numeric 
digit e.g. N2L 3G1 would be the only acceptable format) 
• Phone number with acceptable formats: 123-123-1234, or (123)123-1234 only.
• Email address
• Age (a positive integer greater than or equal to 16)
• Experience (a positive integer greater than or equal to 0). 
Note: the difference between (age) & (experience) has to be greater than or equal to 16.
For instance, a person who is 50 years old cannot have more than 34 years’ experience. 
Number of Accidents (again, a positive integer greater than or equal to 0). 

Fifteen (15) system test cases (using the Selenium Web Driver and NUnit) are created to test this application which include nine mandatory tests as part of the fifteen 
tests (in order): 
1. Your first and last name with all remaining fields with valid data, Age = 25, Driving Experience = 3, Accidents = 0
2. First name omitted with all remaining fields with valid data, Age = 25, Driving Experience = 3, Accidents = 0
3. Last name omitted with all remaining fields with valid data, Age = 26, Driving Experience = 3, Accidents = 0
4. Invalid phone number with all remaining fields with valid data, Age = 27, Driving Experience = 3, Accidents = 0
5. Invalid email address with all remaining fields with valid data, Age = 28, Driving Experience = 3, Accidents = 0
6. Invalid postal code with all remaining fields with valid data, Age = 35, Driving Experience = 17, Accidents = 1
7. Age omitted with all remaining fields with valid data, Age = 36, Driving Experience = 5, Accidents = 0
8. Number of at-fault accidents omitted with all remaining fields with valid data, Age = 37, Driving Experience = 8, Accidents = 0
9. Years of Driving Experience omitted with all remaining fields with valid data, Age = 45. 

The remaining six (6) tests are of my choice that fully tested all the business requirements mentioned above and are unique. Selenium IDE is used to create tests, but ultimately, these tests run through the Visual Studio Test Explorer. 

A video recording is also uploaded here of my tests running.

To deploy this application I ensured: 
1. Apache server is running on my XAMPP, 
2. Extract the application file underneath the XAMPP\htdocs folder. 
4. The link to the application is working on my browser before starting to create any of my testcases.

For this assignment I have used a form of version control, Git through Git Bash. 
