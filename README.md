#Password Generator Code

##Fixes

The Password Generator required some fixes made to its code in order to function properly. 
Below are the following updates made to the original code to allow the website to function as expected.

The code did not have a defined function to allow it to generate a password. The console gave the following error:
script.js:9 Uncaught ReferenceError: generatePassword is not defined
    at HTMLButtonElement.writePassword (script.js:9:18)

Adding the generatePassword function and giving it a loop gave the website the ability to generate a password and provide no errors on the command console. Within the loop the password was given a set length and character set.

Below is an image of the website in working order:


Below is the url to the working and deployed website:


Below is the url to the Github Repository where the code is stored: