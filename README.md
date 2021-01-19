# Automating-college-admission
A Python mini project which assigns admission to 10000 students in 100 colleges.  

LIBRARIES USED : Pandas, itertools, csv, random.

* The enrollment no. and college id are randomly generated and are unique, the marks of 5 subjects and seats of each branch in each college
are randomly generated with boundaries in place. Ranks are assigned to the students based on the total of their marks and collges are too ranked.
* All the students are assigned colleges randomly , each student has 10 choices.
* For the top 200 students , the code is such that they will be assigned only the top 3 colleges with top branches.
* For the rest students , choices are placed in priority order , with college assigned based on availability of seat in the preferred college and branch. 
* Each day 200 students are given admission to their preffered college and branch , and the records are stored in a CSV.
* Each CSV have 200 students and 50 CSV's are generated for all the records.
* RUN THE CODES IN THE FOLL ORDER :
*1)studentdetails.ipynb
*2)collegedetails.ipynb
*3)rank.ipynb
*4)choicedetailsnew.ipynb
*5)Day1admissions.ipynb
*6)admissions.ipynb.

** NOTE : Choice selection and admission asignment takes a lot of time to run as large data sets.




