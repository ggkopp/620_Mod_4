# Requests, JSON, and basic NLP with spaCy

Student: Garrett Kopp

GitHub Link: https://github.com/ggkopp/620_Mod_4

The below questions are answered in the ipynb files which produced the json files. All information has been pushed to the GitHub link above. 

## Questions in Assignment

* (Question 1) Lyrics printed: 1 pt
The following code accesses the lyrics.ovh public api, searches for the lyrics of a song, and stores it in a dictionary object. Write the resulting json to a file (either a JSON file or a pickle file; you choose). You will read in the contents of this file for future questions so we do not need to frequently access the API

* (Question 2) File created and submitted with notebook: 1 pt
Read in the contents of your file. Print the lyrics of the song (not the entire dictionary!) and use spaCyTextBlob to perform sentiment analysis on the lyrics. Print the polarity score of the sentiment analysis. Given that the range of the polarity score is [-1.0,1.0] which corresponds to how positive or negative the text in question is, do you think the lyrics have a more positive or negative connotaion? Answer this question in a comment in your code cell.

* (Question 3) Correct polarity reported: 1 pt
Write a function that takes an artist, song, and filename, accesses the lyrics.ovh api to get the song lyrics, and writes the results to the specified filename. Test this function by getting the lyrics to any four songs of your choice and storing them in different files.

* (Question 4) 
Write a function that takes the name of a file that contains song lyrics, loads the file, performs sentiment analysis, and returns the polarity score. Use this function to print the polarity scores (with the name of the song) of the three files you created in question 3. Does the reported polarity match your understanding of the song's lyrics? Why or why not do you think that might be? Answer the questions in either a comment in the code cell or a markdown cell under the code cell.

