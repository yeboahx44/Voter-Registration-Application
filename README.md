# Voter Registration Application

This application supports voter registration. 
The application launches and runs from the command line prompt. 
The application prompts the user for their first name, last name, age, country of citizenship, state of residence and zipcode.
To be a valid registration all fields must be entered. If they are at least 18 years old and a U.S citizen, they can move forward and be prompted for the remaining questions and register to vote. If not, they will not be presented with the additional questions. 
There is an error checking logic on the input statements to make sure the age numbers entered seem reasonable (e.g. a person is probably not > 120 years) and states should be 2 letters representing only valid U.S. States. 
The application prompts the user for the needed questions to complete the registration and re-prompts when data is invalid giving the user the opportunity to retry. 
The output summarizes the input data and congratulate the user if they are eligible to vote and entered all of the data. 
The user is given options to exit the program at any time to cancel the registration process.


I added a lot of comments to the python code to meet pylint requirement.