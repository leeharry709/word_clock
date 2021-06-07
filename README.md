# word_clock
Displays a word clock with the current time, day of week, and if it's AM or PM.

# Time Setup
This word clock works by displaying different times per 5 minute intervals. For example, 2:55pm would say "IT IS FIVE TO THREE", but 2:59pm would also say the same. So, I made a bunch of if and elif statements that displayed the correct words based on what time interval of 5 minutes it was between.

# "Light-Up" Array
At the beginning of the function, there is an array with a bunch of 0s and a few 1s called "light_array". This will be what determines which cells light up. Within each if and elif statement, it changes a row in the light_array and replaces corresponding cells with 1s.

The array that holds all of the alphabetical letters is "text_array". This will remain static throughout the project as it is the light_array that determinmes the final output.

# Diplaying the Word Clock
Displaying the word clock meant bring the information from one dataframe into another. I took the information from the light_array dataframe by reading which cells had 1s and which cells had 0s and styled the text in the text_array dataframe accordingly. Below are some examples of the output.

![](https://github.com/leeharry709/word_clock/blob/main/media/0140s.png?raw=true)
![](https://github.com/leeharry709/word_clock/blob/main/media/1725s.png?raw=true)
