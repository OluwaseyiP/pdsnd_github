PROJECT TITLE: EXPLORE US BIKESHARE SYSTEM

PROJECT DETAILS
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.
Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

THE DATASET
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:
Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:
Gender
Birth Year

[Data for the first 10 rides in the new_york_city.csv file Close]
The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them (Chicago, New York City, Washington). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns.
Statistics Computed
1.	Popular times of travel (i.e., occurs most often in the start time)
o	most common month
o	most common day of week
o	most common hour of day

2.	Popular stations and trip
o	most common end station
o	most common trip from start to end (i.e., most frequent combination of start station and end station)

3.	Trip duration
o	total travel time
o	average travel time

4.	User info
o	counts of each user type
o	counts of each gender (only available for NYC and Chicago)
o	earliest, most recent, most common year of birth (only available for NYC and Chicago)

SOFTWARE REQUIRED
•	You should have Python 3, NumPy, and pandas installed using Anaconda.
•	A text editor, like Sublime or Atom.
•	A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

UDACITY DATA ANALYST BIKESHARE DATA
This project explores Bike share data from 3 different cities; it uses data from csv files to compute statistics from those 3 cities, also takes user inputs to create an interactive experience.
Built with
•	Python
•	Pandas
•	Numpy
•	Atom 

FILES USED
•	chicago.csv
•	new_york_city.csv
•	washington.csv

CREDITS

The original repo of this is forked from : https://github.com/udacity/pdsnd_github.git 

https://pandas.pydata.org/docs/getting_started/intro_tutorials/09_timeseries.html#min-tut-09-timeseries

https://www.codecademy.com/forum_questions/51d21dc58c1cccb4ab0020e5

https://stackoverflow.com
