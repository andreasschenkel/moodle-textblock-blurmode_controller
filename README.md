
# About this code:</b>  
In some cases when you show an user your moodle course you do not want to show data like name of students for data privacy reason.  
This code can be used to add a blur-functionality to a course so that some data is blured.  
You can turn blur mode on and of using the local storage of the browser to remember the setting on all pages.  
The block has to be configured to be displayed on ALL pages of the course so that the block add the functionality on all pages eg participant page.  

## Blur mode inactive  
![blurinactive.png](documentation/blurinactive.png)

## Blur mode active  
![bluractive.png](documentation/bluractive.png)

This setting is stored in the localstorage of the browser so that the blur feature will be still activ after reloading the page.

The feature might depends on the choosen moodletheme. So please test the features in your moodle and change the selectors if needed.

# Example-blur
## particiant list:
The participant list might look like this:
![participantlist.png](documentation/participantlist.png)



## grader report:
The grader report might look like this:
![participantlist.png](documentation/participantlist.png)

# Additional selectors   
If you need more selectors you can add them in the function changeBlurMode().

Example for the class selector additionalselector:  

Add the following line in the definition of let selector =  

            ".additionalselector,\n" +
