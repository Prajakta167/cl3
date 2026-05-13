if codes ran on vs code 
do following for 
# Relative path
python script.py < data/titanic.csv       #input file passed 

# Absolute path
python script.py < C:/Users/YourName/Downloads/titanic.csv

Save output to a file
python mapper.py < titanic.csv > output.txt



Example Session
python grade_mapper.py

You type:

Alice,95
Bob,78
Charlie,62
David,49

Then press Ctrl + Z + Enter (Windows).

Output:

A	Alice(95)
B	Bob(78)
C	Charlie(62)
F	David(49)

# if want to run mapper and reducer together , create students.txt with sample input
Run Both Together in VS Code

Open terminal and run:

python grade_mapper.py < students.txt | python grade_reducer.py
Final Output
A: Alice(95), Eve(92)
B: Bob(78), Frank(81)
C: Charlie(62)
F: David(49)
