## Link 
 
 - URL to the deployed application  https://liza-p.github.io/password-generator/

## About

 Application that generates a random password based on user-selected criteria. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.


## End to End flow

```
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is written to the page

```


## Note

It is not guaranteed that all selected characters types will be present in the generated password at all times. 

The current implementation randomly chooses characters from the combined set of all selected character sets so there is a chance that characters from one or more selected sets will not be chosen at all by random selection.

