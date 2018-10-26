# Sentiment-Analysis-on-Tweets-with-Geographic-Visualization
Application to discover sentiments of people from different parts of the world on the trending topic based on analysis of tweets. 
________________


Pre-requisites:
1. Anaconda should be installed on you computer device.

Download the following packages and modules in your system if not pre-installed:
1. NumPy
2. Pandas
3. Twitter
4. Tweepy
5. TextBlob
6. Geocoder
7. Bokeh.        

Steps to be followed to run the application in order to get the desired output:
1. Run the program on jupyter notebook using the Anaconda Prompt by the command: jupyter notebook.
2. When the  ipython files are loaded in the browser, open the project file. 
3. From the toolbar, select the Run command for the first cell.
4. Select the hashtag you want to perform analysis on and enter the number of tweets.
5. A pie chart showing the analysed tweets is displayed. The red color in the i.e. chart indicates Negative tweets, Blue color indicates Neutral Tweets and Green color indicates Positive tweets.
6. Then run the second cell. The tweets that were analysed will be plotted on google maps with three different colors.


Parameters to be passed to get the output:
1. When cell 1 is run, enter the serial number (1 to 10)  of the hashtag to be chosen.
2. In the next input box, enter the number of tweets to be extracted for the chosen hashtag. This can be any integer. (Ideally to be chosen between 150-500 to visualise good number of plots on google maps.)


________________


Output Screenshots:


1. When cell1 is run, the top 10 hashtags to be displayed and the way in which input is given:
  
Output_1.png
________________

2. Pie chart 
  
Output_2.png
________________

3. Plot on google map

Output_3.png
________________


NOTE:   
Sentiment Analysis will be performed on the data extracted. 
A pie chart is shown denoting the percentage positive, negative and neutral tweets.
The information about the sentiment for every tweet is maintained in a CSV file.
Location data is extracted for every tweet and processed to store it in the form of location, latitude and longitude.
The CSV file containing the latitude, longitude and sentiment label is then plotted on the google map using Bokeh to get the final output.
