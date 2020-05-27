# Task 1 - REGEX 

Using regular expressions to interpret and manipulate historical text. 

- Installing curl to retrieve a url and output to txt file. 
-- This actually did not work, as it was shown in the discord. Despite Dr. Graham's reccomendations, verifying that curl was installed correctly served no purpose. As seen below 
![](https://github.com/SuppahHacka/week-3/blob/master/curl%20error.PNG) 
  - Also got to try out the previous reccomendation of Dr. Graham to embed the pictures directly into my notes, it worked! 
 - In any case, I used wget to pull the url and output to texas.txt, which worked smoothly. 
 - The next step was not easy at all. I could have sworn I used regex before with my Java API scrapper - to rename my files. However, that was a long time ago. I had difficulty just deleting everything but the table. So I took to google, and this genius thread, pictured below guided me to delete everything that was not needed and saved me a big headache. 
 ![](https://github.com/SuppahHacka/week-3/blob/master/deletesublime.PNG)
 - The rest of the exercise proved to be a little more straightforward. 

# Task 2 - OpenRefine

  Cleaning up the data we modified in REGEX
  - This one failed right off the bat. The OpenRefine project does not contain the columns "Sender" or "recipient" 
   - I tried it again after going back in regex, realizing I forgot a step. Unfortunately, still no difference. Excel spreadsheets show that i've divided my 
    - I believe this time it worked. I had to tell OpenRefine to seperate columns by commas when using CSV files. 
     
     ![](https://github.com/SuppahHacka/week-3/blob/master/openrefine.PNG) 
     
     - Even after the columns were seperated, they were not tagged as "Sender, recipient and date". So I sort of cheated and went back into sublime text, added a line before my data table and went into excel to manually insert my column names ;) 
     - After getting this to work, I followed the instructions to clean up misspells and cluster things together. I wasn't quite able to match the numbers expected in both sender and recipients but managed to get close. 

# Task 3 - Networks
 
- Databsic.io proved to be useless, as I have encountered the same error many others in the discord server were encountering. 
  - My theory is that the website is not able to process such a big data table, like the correspondence we have.
 
- Gephi was quite straightforward and following the steps, with a bit of figuring things out myself seemed to yield quite a promising result! Feel free to validate this claim with the provided file ;) 


# Summary 

This week proved quite frustrating. It just helps proves that Dr. Graham's point of taking breaks after half hour of being stuck is important despite how arrogant I may be. This caused me to often get impatient, skip steps and just laugh about how I spent a bit more time than anticipated fixing something that instructions were already provided for. 

Despite this, I have learned a few neat tricks such as that sublime shortcut to delete a bunch of text!
I was also able to implement some of the feedback from last week, by embedding images as you can clearly see (atleast I hope so) 
