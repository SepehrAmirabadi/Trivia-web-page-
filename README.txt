Name: Sepehr eslami amirabadi
Id :101112474 

Design Choices: 

- test score is printed at the bottom of the page you may have to scroll to see it
- the dropdown will close automatically once you pick an option 
- to close the dropdown without selecting an option simply reclick the button
- after you have used random test your choice for load test must be reset 
	- this occurs because i decided to treat randtest like a 7th tests object that makes use of the load function 

- everything is divided and labeled based on question number and option number for ease of navigation and acsess of info
- the load test button indicates which test it is going to load with the exception of random
	- it is defaulted to the first test
- keep in mind since I implemented the countdown extension, the next question will be loaded when the timer hits 0
regardless of weather everyone has answered or not


extentions added to the specification: 
-feedback button (not very usefull but im not creative and still want the extention marks)	
	- allows user to send feedback on the quiz 
	- since it is only serverside the feedback goes nowhere but it might be usefull for further implementations
- the asthetics of the dropdown button 
- I chose to include the question category when displaying the questions 
- would have added more fetures however the specifications of part one forbids us from including any other attributes 
	-" When the page loads, the page should contain only three elements: a drop-down list populated with each of the test names from the provided dataset"
	