# Capstone-Python-for-everybody
Capstone project for the Specialization "Python for everybody" that included spider, download, process, and visualize 
an email corpus from the Sakai open source project from 2004-2011. This was a large amount of data and required significant 
cleanup to make sense of the data before visualization.


We received from the course the code almost ready and our task was to study the code and its logic, to do some modifications and runs. 

---Crawling and cleaning and analyzing data

Gmane.py: Spiders the repository and it stores all the raw data in a database named content.sqlite and can be interrupted and re-started as often as needed.   
Gmodel.py: it reads the rough/raw data from content.sqlite and produces a cleaned-up and well-modeled version of the data (index.sqlite).
Gbasic.py: It´s the first data analysis, it counts and determines the Top Email list participants and Top Email list organizations.

---Visualization of the data

1)	There is a simple visualization of the word frequency in the subject lines in the files gword.py, this produces the file gword.js which you can visualize using the file gword.htm.
2)	Gline.py visualizes email participation by organizations over time. Its output is written to gline.js which is visualized using gline.htm

*Databases content.sqlite and index.sqlite has not been included in this repository because they are large (> 200MB).

