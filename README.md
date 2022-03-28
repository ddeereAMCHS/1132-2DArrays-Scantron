# Scantron

- Create a program called `Scantron.java`
- Prompt the user for a filename
- The first line is the number of students who took the quiz
- The second line is the number of questions in the quiz
- The third line is the key
- Each subsequent line is a single student's answers
- Read in the data into a 2D array
- Calculate each students grade (out of 100)
- Calculate the percentage of students who got each question right (rounded to one decimal place)
- Determine which student(s) has the highest score

***Example Input:***\
quiz1.txt\
***Example Contents of quiz1.txt:***\
12\
10\
KEY T F F T F T T F T T\
stA T T F T T F T F T T\
stB T F F T T T T F T T\
stC T F T F T F T F T F\
stD T T F T T F T T F T\
stE F F T F F T F F T F\
stF F F T F T F T F F T\
stG T T F T F T F T T F\
stH T T T T T F F F F F\
stI F F F F F T T T T T\
stJ F F T T F F T T F F\
stK T T F F T T F F T T\
stL T T T F F F T T T F\
***Example Output:***\
stA: 70.0\
stB: 90.0\
stC: 60.0\
stD: 50.0\
stE: 50.0\
stF: 40.0\
stG: 60.0\
stH: 30.0\
stI: 70.0\
stJ: 40.0\
stK: 60.0\
stL: 40.0\
Q1: 66.7%\
Q2: 50.0%\
Q3: 50.0%\
Q4: 50.0%\
Q5: 41.7%\
Q6: 41.7%\
Q7: 66.7%\
Q8: 58.3%\
Q9: 66.7%\
Q10: 50.0%\
Highest scorer(s): stB
