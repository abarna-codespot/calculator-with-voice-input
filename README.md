# A smart Calculator
A smart calculator that accepts voice input
![title](https://user-images.githubusercontent.com/39196039/40327390-5369e8e4-5d60-11e8-9e23-424f40325919.jpg)

## Steps for speech recognition
 - For recording, use The SpeechRecognition interface of the Web Speech API.
 - Create a new SpeechRecognition object instance using the SpeechRecognition() constructor
 - Start() of SpeechRecognition will Start the speech recognition service, listening to incoming audio. 
 - The onresult event handler will b Fired when the speech recognition service returns a result, as in it fires when the user stoped speaking. 
 - Finally, get the transcript of the speech recognition. 
 
 ## Steps to manipulate the voice input
 - Set the voice input to the output section of the calcultor & after 2s the output section will be overridden by the result.
 - Define a function called evaluate for the above funationality.
 - Call the evaluate() after 2s using setInterval method in Javascript. 
 - Now, put our eval function under a try catch block. if it works, it will print d result. if it doesn't, it comes to catch block where the output is set to empty & the exception is printed into d console
 
 ## Technology used
 - HTML
 - CSS
 - Javascript
