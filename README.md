# Winton-Kavli-ChatGPT-Dalle-project-creator
This project stems from the project proposal exercise for the Winton-Kavli Workshop 10-14 July 2023.

**NOTE: a ChatGPT API key is needed for this to work! If you don't have one then sadly this will not work for you.**

This was my attempt at automating the Project Proposal exercise we were given, and exploring using chatGPT API keys.

## How this script works:
1.  Randomly selects a student from Cambridge and Berkeley
2.  Takes the data the students gave on the workshop document from the csv file and inputs it into chatGPT and asks it to come up with a research proposal that combines both the projects
3.  Then inputs the title into Dalle, an AI text-to-image generator, and ask for a photo.
4.  This data is then inputted into word.

More effort should be spent on instructing ChatGPT to improve the quality of the proposal. It does an okay job of combining the two projects, and coming up with a title, 
but some of it doesn't make much sense and merely combines the text of the separate projects together instead of trying to accurately combine the projects into 1 project.

Contained: 
1.  A pdf detailing the contents of the workshop
2.  A csv file that contains the data of the attendees given in the pdf. **Name  Cambridge(y/n)  Project title  Project  Keywords**
3.  A python file that picks a random Cambridge & Berkeley student and inputs their data into a chatGPT using a chatGPT API key.
